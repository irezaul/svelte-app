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