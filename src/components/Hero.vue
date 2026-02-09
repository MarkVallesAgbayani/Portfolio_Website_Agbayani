<script setup>

</script>

<template>
    <div class="h-150 flex flex-row items-center justify-around w-full">
        <div class="p-5 flex flex-col gap-5">
            <div class="text-8xl"> 
                <h1 class="font-bold text-sky-900 tracking-normal">Mark Agbayani</h1>
            </div>

            <div class="text-2xl w-175 text-gray-600 tracking-normal">
                <p>Student at STI College exploring how performance, structure, and data come together in real-world systems.</p>
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

        <div class="bg-white/60 w-120 h-120 rounded-4xl border-2 border-gray-50 backdrop-blur-8xl flex items-center justify-center shadow-2xl">
            <div>
                <div>
                    <img class="border-5 border-sky-100 rounded-full w-70 shadow-2xl" src="/public/Images/picture.png" alt="" srcset="">
                    <div class="text-center mt-4 flex flex-col">
                        <p class="font-bold text-2xl tracking-normal"
                        >
                        Mark Agbayani
                        
                        </p>
                        <p class="text-sky-900 uppercase font-medium flex items-center justify-center gap-1 flex-row mt-2"
                        >
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#0c4a6e" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-map-pinned-icon lucide-map-pinned"><path d="M18 8c0 3.613-3.869 7.429-5.393 8.795a1 1 0 0 1-1.214 0C9.87 15.429 6 11.613 6 8a6 6 0 0 1 12 0"/><circle cx="12" cy="8" r="2"/><path d="M8.714 14h-3.71a1 1 0 0 0-.948.683l-2.004 6A1 1 0 0 0 3 22h18a1 1 0 0 0 .948-1.316l-2-6a1 1 0 0 0-.949-.684h-3.712"/></svg>
                        Quezon City</p>
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