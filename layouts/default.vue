<template>
   <div class="flex">
  <div class="bg-black">
    <!-- Sidebar menu -->
    <div class="bg-black  mt-8 text-white w-46 mx-6 flex-none flex flex-col">
      <img class="mx-auto w-48 h-15 mt-4 shadow-lg" src="../assets/img/Spotify_Logo_CMYK_White.png" alt="">
      <ul class="px-3 py-2 pt-8">
        <li class="mb-2">
          <nuxt-link to="/" exact-active-class="font-bold">
            <span class="text-white text-sm hover:text-white transition-colors duration-300 hover:opacity-50 cursor-pointer">Home</span>
          </nuxt-link>
        </li>
        <li class="mb-2">
          <nuxt-link to="/search" exact-active-class="font-bold">
            <span class="text-white text-sm hover:text-white transition-colors duration-300 hover:opacity-50 cursor-pointer">Search</span>
          </nuxt-link>
        </li>
        <li class="mb-8">
          <nuxt-link to="/your-library" exact-active-class="font-bold">
            <span class="text-white text-sm hover:text-white transition-colors duration-300 hover:opacity-50 cursor-pointer">Your Library</span>
          </nuxt-link>
        </li>
        <li class="mb-2">
          <nuxt-link to="/create-playlist" exact-active-class="font-bold">
            <span class="text-white text-sm hover:text-white transition-colors duration-300 hover:opacity-50 cursor-pointer">Create Playlist</span>
          </nuxt-link>
        </li>
        <li class="mb-2">
          <nuxt-link to="/liked-song" exact-active-class="font-bold">
            <span class="text-white text-sm hover:text-white transition-colors duration-300 hover:opacity-50 cursor-pointer">Liked Song</span>
          </nuxt-link>
        </li>
      </ul>

      <div class="px-3">
        <div class="flex gap-4 py-2">
        <p class="text-xs hover:opacity-50 cursor-pointer">Legal</p>
        <p class="text-xs hover:opacity-50 cursor-pointer">Privacy Center</p>
      </div>
      <div class="flex gap-4 py-2">
        <p class="text-xs hover:opacity-50 cursor-pointer">Privacy Policy</p>
        <p class="text-sm hover:opacity-50 cursor-pointer">Cookies</p>
      </div>
      <p class="text-xs py-2 hover:opacity-50 cursor-pointer">About Ads</p>
      <p class="text-xs py-2 mb-4 hover:opacity-50 cursor-pointer">Cookies</p>
      
      <button class="bg-transparent hover:opacity-50 cursor-pointer pb-4text-white border-white border py-2 px-8 rounded-full font-bold">English</button>


      </div>
      
    </div>



    <!-- Main content -->
    
  </div>

  <div class="flex-1">
      <nuxt />
    </div>
  </div>
</template>

<style>
  /* Adjust scrollbar style */
  ::-webkit-scrollbar {
    width: 8px;
  }

  ::-webkit-scrollbar-track {
    background-color: #1f1f1f;
  }

  ::-webkit-scrollbar-thumb {
    background-color: #444;
    border-radius: 9999px;
  }
</style>
