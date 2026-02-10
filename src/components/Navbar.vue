<script setup>

</script>

<template>
    <header class="font-mono fixed-center bg-stone-950 w-60 mt-5 mr-auto ml-auto rounded-full border-1 border-gray-50 shadow-xl backdrop-blur-2xl  md:w-70 lg:w-100">
        <nav>
            <ul class="p-1 flex gap-1 justify-between items-center text-white font-sans text-[10px] font-medium md:text-[14px] lg:text-[16px]">
                <li class="hover:bg-gray-100 p-2 w-30 text-center rounded-full hover:text-gray-900 transition duration-300 cursor-pointer"> 
                    <router-link to="/">
                            Home
                    </router-link>
                </li>
                <li class="hover:bg-gray-100 p-2 w-30 text-center rounded-full hover:text-gray-900 transition duration-300 cursor-pointer"> 
                    <router-link to="/portfolio"> 
                            Portfolio
                    </router-link>
                </li>
                <li class="hover:bg-gray-100 p-2 w-30 text-center rounded-full hover:text-gray-900 transition duration-300 cursor-pointer"> 
                    <router-link to="/contact">
                            Contact
                    </router-link>
                </li>
            </ul>
        </nav>
    </header>
</template>