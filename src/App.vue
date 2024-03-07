<script>
import { RouterLink, RouterView } from 'vue-router'



</script>

<template>
  <header class="grid grid-cols-4 relative w-screen h-[140px] bg-rose-700">
    <h1 class="justify-self-start self-start text-8xl font-bold font-displayFont text-white pl-6 p-[5px]">TULIPANER</h1>
    <nav class="text-white text-4xl font-light col-start-3 col-end-5 self-center font-displayFont ">
      <RouterLink to="/"> home </RouterLink>
      <RouterLink to="/about"> about </RouterLink>
      <a href="https://www.behance.net/helenahollnder" target="_blank" class="hover:bg-rose-500 active:bg-cyan-500"> BeHance </a>
    </nav>
  </header>
  
 
 <RouterView></RouterView>



</template>


<!--Lidt inspiration: https://howtokilladog.com/projects/ -->
