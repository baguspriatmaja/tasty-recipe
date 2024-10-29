<template>
  <div>
    <web-header></web-header>
    <!-- <home-page></home-page> -->
    <router-view></router-view>
    <web-footer></web-footer>
  </div>
</template>

<script setup>
import HomePage from "./components/pages/HomePage.vue"
import WebHeader from "./components/header/WebHeader.vue"
import WebFooter from "./components/footer/WebFooter.vue"
</script>