<script>
  import { Link } from 'svelte-navigator';
</script>

<main>
  
<nav class= "bg-white py-2 md:py-4">
  <div class="container px-4 mx-auto md:flex md:items-center">

    <div class="flex justify-between items-center">
      <Link to="/"class="font-bold text-xl text-indigo-600">MT MART</Link>
      <button class="border border-solid border-gray-600 px-3 py-1 rounded text-gray-600 opacity-50 hover:opacity-75 md:hidden" id="navbar-toggle">
        <i class="fas fa-bars"></i>
      </button>
    </div>

    <div class="hidden md:flex flex-col md:flex-row md:ml-auto mt-3 md:mt-0" id="navbar-collapse">
      
      <Link to="/login" class="p-2 lg:px-4 md:mx-2 text-indigo-600 text-center border border-transparent rounded hover:bg-indigo-100 hover:text-indigo-700 transition-colors duration-300">Login</Link>
      
    </div>
    <Link to="/dashboard" class="w-full px-5 py-3 transition-colors duration-300 bg-gray-100 rounded-md dark:bg-gray-800 md:w-auto md:mx-6 hover:bg-gray-200 dark:hover:bg-gray-700">
      <div class="flex items-center justify-center -mx-1">
          <p class="mx-1 text-sm text-indigo-600 dark:text-white">Apple ID</p>

          <!-- <svg class="w-6 h-6 mx-1 fill-gray-600 dark:fill-white" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
              <path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z" />
          </svg> -->
      </div>
    </Link>
    <Link to="/frp" class="w-full px-5 py-3 transition-colors duration-300 bg-gray-100 rounded-md dark:bg-gray-800 md:w-auto md:mx-6 hover:bg-gray-200 dark:hover:bg-gray-700">
      <div class="flex items-center justify-center -mx-1">
          <p class="mx-1 text-sm text-gray-600 dark:text-white">FRP Bypass</p>
         
      </div>
    </Link>
  </div>
</nav>
</main>