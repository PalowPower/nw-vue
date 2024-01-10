<script setup>
</script>

<template>
  <div class="logocontainer">
    <a href="https://vooras.com" target="_blank">
      <img src="/v_logo_small_sq.png" class="logo vooras" alt="Vooras" />
      <h1>Caption</h1>
    </a>
    <a>
      <img src="/vite.svg" class="logo vite" alt="Vite">
      <h1>Caption</h1>
    </a>
  </div>
</template>

<style scoped>
.logocontainer {
  justify-content: space-between;
  display: inline-flex;
  column-gap: 5em;
}
.logo {
  height: 10em;
  padding: 2em;
  will-change: filter;
  transition: height 1s;
}
.logo:hover {
  filter: drop-shadow(0 0 3em #646cffaa);
  height: 15em;
  transition: height 0.7s;
}
.logo.vooras {

}
</style>
