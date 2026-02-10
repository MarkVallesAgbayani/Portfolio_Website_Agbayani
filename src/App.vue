<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'

</script>

<template>
  <!-- <Navbar></Navbar>
  <Hero></Hero> -->

  <div class="flex flex-col text-white justify-center items-center h-screen bg-stone-900 font-mono">
    <div class="text-center flex flex-col justify-center items-center w-300 gap-10">
          <h1 class="text-center font-bold mt-10 text-7xl">Welcome to My Portfolio</h1>
          <p class="text-2xl">This project is currently under development.  
              I’m actively building features and improving the UI.
          </p>
          <div class="text-center flex flex-row gap-5">
            <a href="https://github.com/MarkVallesAgbayani" target="_blank" class="bg-stone-950 hover:bg-sky-800 transition duration-300 text-white font-bold rounded p-3">GitHub </a>
            <a href="https://www.linkedin.com/in/mark-lui-agbayani-238292324/" target="_blank" class="bg-stone-950 hover:bg-sky-800 transition duration-300 text-white font-bold rounded p-3">LinkedIn </a>
          </div>
          <p class="bg-sky-950 w-120 h-10 p-2 text-center rounded-md">Tech Stack: Vue.js, Vite, Tailwind CSS</p>
    </div>
  </div>
      <footer class="text-center p-4 text-white fixed bottom-0 w-full">© 2026 Mark Agbayani. All rights reserved.</footer>
</template>

