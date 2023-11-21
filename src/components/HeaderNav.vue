<template>
  <header class="header">
    <nav class="nav">
      <h1 class="logo red-title">清廉</h1>
      <h1 class="logo">公报</h1>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
.header {
  width: 100vw;
  position: sticky;
  top: 0;
  left: 0;
  z-index: 50;
  border-bottom: 1px solid #000;
  background: #fff;
  padding: 0 5rem;
  &::after {
    z-index: -1;
    position: absolute;
    content: '';
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    opacity: 0.3;
    background: url('/img/bg.png');
    background-attachment: fixed;
  }
}
.nav {
  height: 80px;
  margin: 0 auto;
  display: flex;
  align-items: center;
}
.logo {
  font-size: 2rem;
  font-family: SanFont;
}

.red-title {
  background: red;
  color: white;
  padding: 0 0.5rem;
}
</style>
