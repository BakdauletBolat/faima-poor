<script setup lang="ts">
import back from './assets/images/f04d2ac7-2d4f-49fa-9c1f-e49fc962fa58.jpeg';
</script>

<template>
  <header class="container">
    <nav class="nav">
      <div class="logo">_f22a</div>
      <ul>
        <li class="mob-v nav-item">О нас</li>
        <li class="mob-v nav-item">Проекты</li>
        <li class="nav-item"><button class="btn">Связаться</button></li>
      </ul>
    </nav>
  </header>
  <main>
    <div class="container">
      <div class="hero">
        <h1 class="hero__title">Сделай <span class="spec-text">свой дом</span> радости</h1>
        <p class="hero__desc">Мы превращаем ваш пустой дом в уютное жилище, используя мебель, экономящую пространство. Воплощаем уникальные ваши вкусы в реальность!</p>
      </div>
    </div>

    <div class="main-slider">
      <div class="container get-container">
        <div class="get-in-out">
        <div class="get-in">
        </div>
      </div>
      </div>
      
      <div class="main-image-container"><img class="main-image" :src="back"></div>
    </div>
  </main>
</template>

<style scoped></style>
