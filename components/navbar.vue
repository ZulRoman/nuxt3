<template>
<nav class="bg-transparent absolute flex justify-end">
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
    <button data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-default" aria-expanded="false">
      <span class="sr-only">Open main menu</span>
      <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
    </button>
    <div class="hidden w-full md:block md:w-auto" id="navbar-default">
      <ul class="font-medium flex flex-col p-4 md:p-0 mt-4 md:flex-row md:space-x-8 md:mt-0 md:border-0">
        <li class="group">
                                    <nuxt-link to="/"
                                        class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">Home</nuxt-link>
                                </li>
                                <li class="group">
                                    <nuxt-link to="/about"
                                        class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">About</nuxt-link>
                                </li>
      </ul>
    </div>
  </div>
</nav>

</template>
