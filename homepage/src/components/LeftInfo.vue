<script setup lang="ts">
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap/dist/js/bootstrap.min.js';
</script>

<template>
    <div class="card card_redef" style="">
        <img src="../assets/photo.jpg" class="card-img-top round-icon" alt="...">
        <div class="card-body">
            <p class="name-style">
                Xiaochen Li
            </p>
            <p class="name-style">
                李晓晨
            </p>
            <p class="list-style">
                西北大学 学士
            </p>
            <p class="list-style">
                西北工业大学 硕士在读
            </p>
            <p class="list-style">
                lxcwuwang365@163.com
            </p>
            <p class="list-style">
                我是一名西北工业大学在读硕士生，师从刘思聪老师。研究兴趣包括但不限于边缘计算、联邦学习、容器虚拟化等。
            </p>
        </div>
    </div>
    <span class="placehold"></span>
</template>

<style scoped>
.round-icon {
    text-align: center;
    width: 100%;
    display: inline-flex;
    border-radius: 50%;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

.card_redef {
    border-radius: 0%;
    position: fixed;
    padding-top: 5%;
    padding-left: 1%;
    padding-right: 1%;
    text-align: center;
    border: none;
    width: 15%;
    height: 100%;
    background-color: rgb(6, 199, 135);
}

.name-style {
    font-size: 150%;
    color: white;
    font-weight: 800;
}

.list-style{
    color: white;
    font-size: 100%;
    font-weight: 800;
}

.placehold{
    border-radius: 0%;
    padding-top: 5%;
    padding-left: 1%;
    padding-right: 1%;
    text-align: center;
    border: none;
    width: 30%;
    display: inline-block;
    /* height: 100%; */
}
</style>