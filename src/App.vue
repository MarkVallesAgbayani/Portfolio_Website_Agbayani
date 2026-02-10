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

              <a href="https://github.com/MarkVallesAgbayani" target="_blank" class="bg-stone-950 flex gap-2 hover:bg-sky-800 transition duration-300 text-white font-bold rounded p-3"
              >
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-github-icon lucide-github"><path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"/><path d="M9 18c-4.51 2-5-2-7-2"/></svg>
              GitHub 
            </a>

            <a href="https://www.linkedin.com/in/mark-lui-agbayani-238292324/" target="_blank" class="bg-stone-950 flex gap-2 hover:bg-sky-800 transition duration-300 text-white font-bold rounded p-3"
              >
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-linkedin-icon lucide-linkedin"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"/><rect width="4" height="12" x="2" y="9"/><circle cx="4" cy="4" r="2"/></svg>
              LinkedIn 
            </a>

          </div>
          <p class="bg-sky-950 w-120 h-10 p-2 text-center rounded-md flex gap-3 items-center justify-center">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-layers-icon lucide-layers"><path d="M12.83 2.18a2 2 0 0 0-1.66 0L2.6 6.08a1 1 0 0 0 0 1.83l8.58 3.91a2 2 0 0 0 1.66 0l8.58-3.9a1 1 0 0 0 0-1.83z"/><path d="M2 12a1 1 0 0 0 .58.91l8.6 3.91a2 2 0 0 0 1.65 0l8.58-3.9A1 1 0 0 0 22 12"/><path d="M2 17a1 1 0 0 0 .58.91l8.6 3.91a2 2 0 0 0 1.65 0l8.58-3.9A1 1 0 0 0 22 17"/></svg>
            Tech Stack: Vue.js + Vite, Tailwind CSS.
          </p>
    </div>
  </div>
<footer class="text-center p-4 text-white fixed bottom-0 w-full">© 2026 Mark Agbayani. All rights reserved.</footer>
</template>

