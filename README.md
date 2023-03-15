# Svelte 

## Process
* Create a svelte project by blank or chosse on a tamplate 
``` base 
npm init vite . --template svelte
```
*  initialize npm on project folder `npm install `

* check working or not via command `npm run dev`
* install git hub gh-pages via command `npm i -D gh-pages`
* check by build `npm run build`
* now its time to build `npm run deploy`

* check `dist` folder come to on your project folder ... ENJOY@


### Page Navigation 

* install page navigation `npm install --save svelte-navigator`
* on Route page use this 
```svelte
<script>
     import { Route, Router } from 'svelte-navigator';
     import Header from '../Pages/Header.svelte';
     import Home from '../Pages/Home.svelte';
     import Login from '../Pages/Login.svelte';
   
   
</script>

<main>
    <Router>
        <Header />
        <Route path="/">
          <Home />
        </Route>
        <Route path="/login">
          <Login />
        </Route>
    
      </Router>
     
</main>
```