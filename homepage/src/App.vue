<script setup lang="ts">

import { reactive } from 'vue'
import "bootstrap/dist/css/bootstrap.min.css"
import Info from "./components/Infos.vue"
import LeftInfo from './components/LeftInfo.vue';

var changeBlank = function () {
  var width = document.documentElement.clientWidth;
  var height = document.documentElement.clientHeight;
  var percent:number = 0.7
  var extraWidth = (width - percent * height) > 0 ? (width - percent * height) : 0
  var margin_percent = extraWidth / 2 / width
  let margin_percent_str:string = (margin_percent*100).toString()+"%"
  return margin_percent_str
}


const margin_control = reactive({marginLeft:changeBlank(),marginRight:changeBlank()})


window.onload = function () {
  margin_control.marginLeft = changeBlank()
  margin_control.marginRight = changeBlank()
}
window.onresize = function () {
  margin_control.marginLeft = changeBlank()
  margin_control.marginRight = changeBlank()
}

</script>

<template>
  <div class="main-redef" :style="margin_control">

    <LeftInfo></LeftInfo>
    <Info></Info>
  </div>
</template>

<style scoped>
.main-redef {
  background-color: white;
  min-height: 100%;
}
</style>
