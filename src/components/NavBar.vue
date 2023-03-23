<script setup>
import { RouterLink } from 'vue-router'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
</script>

<template>
    <nav>
        <RouterLink to="/"><ToolingIcon class="icon" /></RouterLink>
        <RouterLink to="/about"><EcosystemIcon class="icon"/></RouterLink>
    </nav>
</template>

<style scoped>
nav {
    background-color: var(--dark-blue);
    height: 100vh;
    padding: 48px 12px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.icon {
    color: var(--soft-yellow);
    height: 16px;
}
</style>