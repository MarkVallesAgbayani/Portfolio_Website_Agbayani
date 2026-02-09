<script setup>

</script>

<template>
    <div class="h-150 flex flex-row items-center justify-around">
        <div class="p-5 flex flex-col gap-5">
            <div class="text-8xl font-sans"> 
                <h1 class="font-sans font-bold text-sky-900">Mark Agbayani</h1>
            </div>

            <div class="text-2xl w-140">
                <p class="font-sans">Computer Science student at STI College crafting high-performance
                    systems and data-driven solutions.</p>
            </div>

            <div class="gap-3 flex">
                <button class="bg-sky-800 shadow-2xl text-white p-5 rounded-full text-sm flex gap-2 cursor-pointer"  type="button" 
                >
                    View Projects 
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right-icon lucide-arrow-right"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg> 
                </button>
                <button class="bg-none shadow-2xl text-black p-4 w-50 rounded-full border-1 text-sm cursor-pointer" type="button"
                >
                    Download Resume
                </button>
            </div>
        </div>

        <div class="picture bg-white/60 w-120 h-120 rounded-4xl border-2 border-gray-50 backdrop-blur-8xl flex items-center justify-center shadow-2xl">
            <div>
                <div>
                    <img class="border-5 border-amber-50 rounded-full w-70 shadow-2xl" src="/public/Images/picture.png" alt="" srcset="">
                    <div class="text-center mt-4 flex flex-col gap-1">
                        <p class="font-bold text-2xl">Mark Agbayani</p>
                        <p class="text-sky-900 uppercase font-medium">CS @ STI College</p>
                        <div class="mt-10 flex gap-1 justify-center items-center">
                            <p class="border-gray-400 border-1 text-sm text-center p-3 rounded-full bg-gray-100">4th Year</p>
                            <p class="border-gray-400 border-1 text-sm text-center p-3 rounded-full bg-gray-100">Developer Intern</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>