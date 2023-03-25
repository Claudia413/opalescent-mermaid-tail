<script setup>
import { RouterLink } from 'vue-router'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
</script>

<template>
    <nav>
        <RouterLink to="/" class="link"><ToolingIcon class="icon" /></RouterLink>
        <RouterLink to="/about" class="link"><EcosystemIcon class="icon"/></RouterLink>
    </nav>
</template>

<style scoped lang="scss">
nav {
    background-color: var(--blue-800);
    height: 100vh;
    width:100px;
    padding: 48px 30px 48px 45px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.link {
    margin-bottom: 36px;
    &:hover .icon{
        color: var(--soft-yellow);
        opacity: 1;
    }
}
.icon {
    color: var(--blue-100);
    height: 24px;
    opacity: 0.7;
    
}
</style>