<script setup>
import HomePage from './pages/HomePage.vue'
import HeaderNav from './components/HeaderNav.vue'
import ProgressLine from './components/ProgressLine.vue'
import PoetryPage from './pages/PoetryPage.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div class="bg"></div>
  <HeaderNav />

  <main class="main">
    <ProgressLine />
    <HomePage />
    <PoetryPage />
  </main>

  <Footer />
</template>

<style scoped lang="scss">
.main {
  position: relative;
}
.bg {
  height: 100vh;
  width: 100vw;
  position: fixed;
  z-index: -1;
  background: url('/img/bg.png');
  background-attachment: fixed;
  opacity: 0.3;
  background-size: cover;
}
</style>
