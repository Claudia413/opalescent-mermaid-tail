<script setup>
import NavBar from '../components/NavBar.vue';
</script>

<template>
  <main>
    <div class="content">hello</div>
    <div class="pages"></div>
    <NavBar></NavBar>
  </main>
</template>

<style lang="scss">

main{
  display: grid;
  grid-template-columns: auto 32px 100px;
  max-width: 100vw;
  overflow: hidden;
}

.content {
  background: linear-gradient(90deg, rgba(244,243,238,1) 8%, rgba(227,227,219,1) 16%, rgba(227,227,219,1) 20%, rgba(200,199,194,1) 23%, rgba(210,210,202,1) 25%, rgba(233,232,225,1) 28%, rgba(244,243,238,1) 32%);
}

.pages {
  width: 100%;
  background-image: repeating-linear-gradient(to right, #e7e8e7, #e7e8e7 1.5px, var(--cream-white-300) 1.5px, transparent);
  background-size: 4px 10px;
}

</style>