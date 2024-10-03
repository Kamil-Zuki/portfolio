<template>
    <header>
        <NavBar />
    </header>
</template>

<script setup>
import NavBar from './NavBar.vue';


</script>

<style scoped>
header{
    margin-top: 20px;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 1rem 9%;
    background-color: transparent;
    filter: drop-shadow(10px);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

</style>