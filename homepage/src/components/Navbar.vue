<script setup lang="ts">
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap/dist/js/bootstrap.min.js';

</script>

<template>
    <span class="navbar-style">
        <span class="nav-block-style">1</span>
        <span class="nav-block-style">1</span>
        <span class="nav-block-style">1</span>
        <span class="nav-block-style">1</span>
    </span>
</template>

<style scoped>

.navbar-style{
    text-align: center;
    position: fixed;
    background-color: rgb(255, 255, 255);
    width: 35%;
}
.nav-block-style{
    width: 25%;
    margin: 0;
    display: inline-block;
    font-size: 150%;
}

</style>