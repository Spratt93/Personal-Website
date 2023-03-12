<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import AboutView from './views/AboutView.vue'
</script>

<template>
    <main>
        <Navbar />
        <RouterView />
    </main>
</template>