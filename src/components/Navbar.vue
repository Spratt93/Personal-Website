<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
    <div class="navbar">
        <ul>
            <li>
                <RouterLink to="/">Home</RouterLink>
            </li>
            <li>
                <RouterLink to="/projects">Projects</RouterLink>
            </li>
            <li>
                <RouterLink to="/experience">Experience</RouterLink>
            </li>
        </ul>
    </div>
</template>

<style scoped>
.navbar {
    padding: 2em;
    position: fixed;
    top: 0em;
}

ul {
    list-style-type: none;
    width: 40em;
}

li {
    float: left;
    margin-left: 5em;
}</style>