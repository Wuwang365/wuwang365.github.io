<script setup lang="ts">
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap.min.js"
</script>

<template>
  <div class="info-block">
    <div class="info-label">
      Publication
    </div>


    <div class="card mb-3 card_limit">
      <img src="../assets/adaenlight.png" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title"><a href="https://dl.acm.org/doi/abs/10.1145/3569464">AdaEnlight: Energy-aware Low-light Video Stream Enhancement on Mobile Devices</a></h5>
        <p class="card-text">Sicong Liu, <span class="outstanding-green">Xiaochen Li </span>, Zimu Zhou, Bin Guo, Meng
          Zhang, Haocheng Shen, Zhiwen Yu</p>
        <p class="card-text"><span class="outstanding-green">ACM Ubicomp 2023 </span> <span class="outstanding-red">CCF-A
          </span></p>
      </div>
    </div>
    

    <div class="authors"></div>
  </div>
</template>

<style scoped>
.info-block {
  display: inline-block;
  width: 69%;
  padding-left: 5%;
  padding-top: 5%;
  padding-right: 5%;
  vertical-align: top;
}

.info-label {
  font-weight: 800;
  font-size: 150%;
  font-style: "Arial";
}


.authors {
  font-weight: 400;
  font-size: 100%;
  font-style: "Arial";
}

.outstanding-green {
  color: rgb(6, 199, 135);
}

.outstanding-red {
  color: red;
}

a{
  text-decoration:none;
color: #000;
}

.card_limit{
  max-width: 100%;
}
</style>
