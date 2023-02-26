<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/Infos.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import Info from "./components/Infos.vue"
import LeftInfo from './components/LeftInfo.vue';
</script>

<template>
<div class="main-redef">
  
  <LeftInfo></LeftInfo>
  <Info></Info>
</div>
</template>

<style scoped>

.main-redef{
  margin-left: 25%;
  margin-right: 25%;
  background-color: white;
  height: 100%;
  
}
</style>
