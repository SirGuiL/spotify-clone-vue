<script setup>
import Link from '../atoms/Link.vue';

</script>

<template>
    <nav class="flex-1">
        <ul class="flex justify-end flex-1">
            <Link message="Premium" />
            <Link message="Ajuda" />
            <Link message="Baixar" />
            <li class="px-4">
                <span class="border-r border-white"></span>
            </li>
            <Link message="Inscrever-se" />
            <Link message="Log In" />
        </ul>
    </nav>
</template>
<style scoped>
</style>
