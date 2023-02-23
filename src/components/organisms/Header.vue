<script setup>
import LinksContainer from '../molecules/LinksContainer.vue'
</script>

<template>
    <header>
        <div class="flex fixed bg-black w-full px-3 md:px-20 py-4">
            <div class="container flex items-center mx-auto">
                <div>
                    <a href="#">
                        <img src="img/spotify-logo.png" alt="Spotify" class="w-20 md:w-125px">
                    </a>
                </div>
                <div class="flex justify-end flex-1 md:hidden text-white text-3xl">
                    <i class="fas fa-bars"></i>
                </div>
                <div class="items-end flex-1 text-white font-bold hidden md:flex">
                    <LinksContainer />
                </div>
            </div>
        </div>
    </header>
</template>
<style scoped>
</style>
