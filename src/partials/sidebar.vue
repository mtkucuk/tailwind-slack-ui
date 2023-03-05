<template>

  <aside class="overflow-auto h-full  text-gray-100 px-4 py-2">
    <div class="flex mb-4">
      <div class="relative inline-block ">
        <img class="w-12 h-8 rounded-full border-1 border-white" src="../assets/images/user-1.png"/>
        <span class="w-2 h-2 rounded-full bg-green-500 border-1 border-white absolute bottom-1.5 left-10"></span>
      </div>
      <div class="ml-2 text-sm w-full">
        <strong class="w-full">Jonh Kenedy</strong>
        <br>
        <span class="w-full pl-3">@john</span>
      </div>
      <div>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
             stroke="currentColor" class="w-4 h-4">
          <path stroke-linecap="round" stroke-linejoin="round"
                d="M14.857 17.082a23.848 23.848 0 005.454-1.31A8.967 8.967 0 0118 9.75v-.7V9A6 6 0 006 9v.75a8.967 8.967 0 01-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 01-5.714 0m5.714 0a3 3 0 11-5.714 0"/>
        </svg>

      </div>
    </div>
    <ul>
      <li class="mb-2">
        <a href="#" class="text-slate-400	 hover:text-white text-sm flex">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="w-4 h-4 mr-1">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="M8.625 9.75a.375.375 0 11-.75 0 .375.375 0 01.75 0zm0 0H8.25m4.125 0a.375.375 0 11-.75 0 .375.375 0 01.75 0zm0 0H12m4.125 0a.375.375 0 11-.75 0 .375.375 0 01.75 0zm0 0h-.375m-13.5 3.01c0 1.6 1.123 2.994 2.707 3.227 1.087.16 2.185.283 3.293.369V21l4.184-4.183a1.14 1.14 0 01.778-.332 48.294 48.294 0 005.83-.498c1.585-.233 2.708-1.626 2.708-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0012 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018z"/>
          </svg>

          Threads</a>
      </li>
      <li class="mb-2"><a href="" class="text-slate-400	 hover:text-white text-sm flex">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
             stroke="currentColor" class="w-4 h-4 mr-1">
          <path stroke-linecap="round" stroke-linejoin="round"
                d="M20.25 8.511c.884.284 1.5 1.128 1.5 2.097v4.286c0 1.136-.847 2.1-1.98 2.193-.34.027-.68.052-1.02.072v3.091l-3-3c-1.354 0-2.694-.055-4.02-.163a2.115 2.115 0 01-.825-.242m9.345-8.334a2.126 2.126 0 00-.476-.095 48.64 48.64 0 00-8.048 0c-1.131.094-1.976 1.057-1.976 2.192v4.286c0 .837.46 1.58 1.155 1.951m9.345-8.334V6.637c0-1.621-1.152-3.026-2.76-3.235A48.455 48.455 0 0011.25 3c-2.115 0-4.198.137-6.24.402-1.608.209-2.76 1.614-2.76 3.235v6.226c0 1.621 1.152 3.026 2.76 3.235.577.075 1.157.14 1.74.194V21l4.155-4.155"/>
        </svg>

        Direct messages</a></li>
      <li class="mb-2"><a href="" class="text-slate-400	 hover:text-white text-sm flex">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
             stroke="currentColor" class="w-4 h-4 mr-1">
          <path stroke-linecap="round"
                d="M16.5 12a4.5 4.5 0 11-9 0 4.5 4.5 0 019 0zm0 0c0 1.657 1.007 3 2.25 3S21 13.657 21 12a9 9 0 10-2.636 6.364M16.5 12V8.25"/>
        </svg>

        Mentions & reactions</a></li>
      <li class="mb-2"><a href="" class="text-slate-400	 hover:text-white text-sm flex">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
             stroke="currentColor" class="w-4 h-4 mr-1">
          <path stroke-linecap="round" stroke-linejoin="round"
                d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5"/>
        </svg>

        Drafts & sent</a></li>
      <li class="mb-2"><a href="" class="text-slate-400	 hover:text-white text-sm flex">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
             stroke="currentColor" class="w-4 h-4 mr-1">
          <path stroke-linecap="round" stroke-linejoin="round"
                d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0111.186 0z"/>
        </svg>

        Saved items</a></li>
      <li class="mb-2"><a href="" class="text-slate-400	 hover:text-white text-sm flex">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
             stroke="currentColor" class="w-4 h-4 mr-1">
          <path stroke-linecap="round" stroke-linejoin="round"
                d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008z"/>
        </svg>

        Slack Connect</a></li>
      <li class="mb-2"><a href="" class="text-slate-400	 hover:text-white text-sm flex">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
             stroke="currentColor" class="w-4 h-4 mr-1">
          <path stroke-linecap="round" stroke-linejoin="round"
                d="M12 6.75a.75.75 0 110-1.5.75.75 0 010 1.5zM12 12.75a.75.75 0 110-1.5.75.75 0 010 1.5zM12 18.75a.75.75 0 110-1.5.75.75 0 010 1.5z"/>
        </svg>

        More</a></li>

    </ul>
    <div class="w-full border border-slate-800	mt-4 mb-4"></div>
    <h2 class="text-md text-slate-400   mb-4 flex  hover:text-white">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
           stroke="currentColor" class="w-4 h-4 mr-1 mt-1">
        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5"/>
      </svg>

      Channels <span class="text-sm ml-1">(39)</span></h2>
    <ul>
      <li class="mb-2">
        <a href="#" class="text-slate-400	 hover:text-white text-sm flex">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="w-4 h-4 mr-1">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="M16.5 10.5V6.75a4.5 4.5 0 10-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H6.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z"/>
          </svg>

          general</a>
      </li>
      <li class="mb-2">
        <a href="#" class="text-slate-400	 hover:text-white text-sm flex ">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="w-4 h-4 mr-1">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="M5.25 8.25h15m-16.5 7.5h15m-1.8-13.5l-3.9 19.5m-2.1-19.5l-3.9 19.5"/>
          </svg>
          random</a>
      </li>
      <li class="mb-2">
        <a href="#" class="text-slate-400	 hover:text-white text-sm flex">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="w-4 h-4 mr-1">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="M5.25 8.25h15m-16.5 7.5h15m-1.8-13.5l-3.9 19.5m-2.1-19.5l-3.9 19.5"/>
          </svg>
          design</a>
      </li>
      <li class="mb-2">
        <a href="#" class="text-slate-400	 hover:text-white text-sm flex">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="w-4 h-4 mr-1">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="M5.25 8.25h15m-16.5 7.5h15m-1.8-13.5l-3.9 19.5m-2.1-19.5l-3.9 19.5"/>
          </svg>
          development</a>
      </li>
    </ul>
    <div class="w-full border border-slate-800	mt-4 mb-4"></div>
    <h2 class="text-md  text-slate-400 mb-4 flex hover:text-white">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
           stroke="currentColor" class="w-4 h-4 mr-1 mt-1">
        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5"/>
      </svg>
      Direct messages
    </h2>
    <ul>
      <li class="mb-2" v-for="i of 15" :key="i">
        <a href="#" class="text-slate-400	 hover:text-white text-sm">
          <div class="flex">
            <div class="relative inline-block ">
              <img class="w-6 h-6 rounded-sm border-1 border-white" src="../assets/images/user-1.png"/>
              <span
                  class="w-2 h-2 rounded-full bg-green-500 border-1 border-white absolute bottom-0.5 right-0.5"></span>
            </div>
            <div class="ml-2">
              {{ i }}.kişi
            </div>
          </div>
          <!--             -->
        </a>
      </li>
      <li class="mb-2 mt-2">
        <a href="#" class="text-slate-400	 hover:text-white text-sm flex">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
               stroke="currentColor" class="w-4 h-4 mr-1 bg-slate-800	 ">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15"/>
          </svg>

          Add teammates</a>
      </li>
    </ul>
  </aside>
</template>

<script>
export default {
  name: "partials-sidebar"
}
</script>

<style scoped>

</style>