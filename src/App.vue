<template>
    <Header />
    <div class="h-[120px] fixed top-0">header</div>
    <div class="main">
        <main>main</main>
        <div>footer</div>
    </div>
    <!-- <RouterView /> -->
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from '@/components/the-header.vue'
</script>

<style scoped>
.main {
    height: 100svh;
    display: flex;
    flex-direction: column;
    padding-top: 120px;
}
main {
    display: flex;
    flex-grow: 1;
    justify-content: center;
    position: relative;
    z-index: 2;
}
</style>
