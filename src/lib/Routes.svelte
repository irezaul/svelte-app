<script>
  import { Route, Router } from "svelte-navigator";
  import Dashboard from "../Pages/Dashboard.svelte";
  import Frp from "../Pages/Frp.svelte";
  import Header from "../Pages/Header.svelte";
  import Home from "../Pages/Home.svelte";
  import Login from "../Pages/Login.svelte";
  import NotFound from "../Pages/NotFound.svelte";

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
    <Route path="/dashboard">
      <Dashboard />
    </Route>
    <Route path="/frp">
      <Frp />
    </Route>
  
    <Route path="/svelte-app/*">
      <NotFound />
    </Route>
  </Router>
</main>
