<script setup>

</script>

<template>
    <header class="fixed-center bg-white w-60 mt-5 mr-auto ml-auto rounded-full shadow-xl backdrop-blur-2xl border-1 border-gray-100 md:w-70 lg:w-100">
        <nav>
            <ul class="p-1 flex gap-1 justify-between items-center text-gray-600 font-sans text-[10px] font-medium md:text-[14px] lg:text-[16px]">
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