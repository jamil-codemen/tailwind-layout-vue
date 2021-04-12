<template>
  <div class="text-gray-700 grid md:grid-cols-3">

    <div class="md:col-span-1 md:flex md:justify-end">
      <nav class="text-right">
        <div class="flex justify-between items-center">
          <h1 class="font-bold uppercase p-4 border-b border-gray-100">
            <a class="text-green-500 sm:text-red-500 lg:text-blue-500 hover:text-gray-700" href="/">Recipe Lad</a>
          </h1>
          <div class="px-4 cursor-pointer md:hidden" id="burger">
            <svg  xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
</svg>
          </div>
        </div>
        <ul class="text-sm mt-6 hidden md:block " id="menu">
          <li class="text-gray-500 font-bold">
            <a href="#" class="px-4 flex justify-end border-r-4 border-red-400">
              <span>Home</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-5 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
</svg>
            </a>
          </li>
          <li>
            <a href="#" class="px-4 flex justify-end">
              <span>About</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-5 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>
            </a>
          </li>
          <li>
            <a href="#" class="px-4 flex justify-end">
              <span>Contact</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-5 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z" />
</svg>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  
    <main class="px-16 py-16 bg-gray-100 md:col-span-2">
      <div class="flex justify-center md:justify-end">
        <a class="rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider border-primary md:border-2 hover:bg-white hover:text-red-500 transition ease-out duration-500" href="#">Log in</a>
        <a class="rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider border-primary md:border-2 hover:bg-white hover:text-red-500 transition ease-out duration-500" href="#">Sign up</a>
      </div>
      <div class="flex items-center justify-center">
        <div class="bg-red-500 h-4 w-6"></div>
        <div class="bg-blue-500 h-8 w-6"></div>
        <div class="bg-green-500 h-12 w-6"></div>
      </div>
      <header>
        <h2 class="text-gray-700 text-6xl font-semibold">Recipes</h2>
        <h3 class="text-2xl font-semibold">For Foodies</h3>
      </header>

      <div>
        <h4 class="font-bold mt-12 pb-2 border-b border-gray-200" >Latest Recipes</h4>
  
        <div class="mt-8 grid lg:grid-cols-3 gap-10">
          <!-- cards go here -->
          <div class="bg-white rounded overflow-hidden shadow-lg relative"> 
            <img src="../../assets/food.jpg" alt="stew" class="w-full h-72 sm:h-48 object-cover" >
            <div class="m-4">
              <span class="font-bold">Mix Salad</span>
              <span class="block text-gray-500 text-sm">Recipe by Mario</span>
            </div>
            <div class="bg-gray-200 text-gray-600 text-xs uppercase font-bold rounded-full p-2 absolute top-0 ml-2 mt-2">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-5 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>
              <span>25mins</span>
              </div>
          </div>
          <div class="bg-white rounded overflow-hidden shadow-lg relative"> 
            <img src="../../assets/foods.jpg" alt="stew" class="w-full h-72 sm:h-48 object-cover" >
            <div class="m-4">
              <span class="font-bold">Chilli Soup</span>
              <span class="block text-gray-500 text-sm">Recipe by Mario</span>
            </div>
            <div class="bg-gray-200 text-gray-600 text-xs uppercase font-bold rounded-full p-2 absolute top-0 ml-2 mt-2">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-5 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>
              <span>25mins</span>
              </div>
          </div>
          <div class="bg-white rounded overflow-hidden shadow-lg relative"> 
            <img src="../../assets/foodt.jpg" alt="stew" class="w-full h-72 sm:h-48 object-cover" >
            <div class="m-4">
              <span class="font-bold">Paninja Salad</span>
              <span class="block text-gray-500 text-sm">Recipe by Mario</span>
            </div>
            <div class="bg-gray-200 text-gray-600 text-xs uppercase font-bold rounded-full p-2 absolute top-0 ml-2 mt-2">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-5 inline-block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>
              <span>25mins</span>
              </div>
          </div>
        </div>

        <h4 class="font-bold mt-12 border-b border-gray-200"> Most Popular</h4>

        <div class="mt-8">
          <!-- cards go here -->
        </div>
      </div>

      <div class="flex justify-center">
        <div class="bg-secondary-100 text-secondary-200 rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider border-primary md:border-2 hover:bg-white hover:text-red-500 hover:shadow-inner transform hover:scale-125 transition ease-out duration-500">Load more</div>
      </div>  
    </main>
  </div>
</template>

<script>

export default {
  name: 'Hero',
};
// const burger =document.querySelector('#burger');
// const menu =document.querySelector('#menu');
// burger.addEventListener('click',()=>{
//   if(menu.classList.contains('hidden')){
//     menu.classList.remove('hidden');
//   }else {
//     menu.classList.add('hidden');
//   }
// })

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
