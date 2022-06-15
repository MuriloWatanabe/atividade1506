<script></script>
<template>
  <header class="menu-superior">
    <div class="menu-esquerdo">
      <span><RouterLink to="/">Home</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/about">Sobre</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/jogos">Jogos</RouterLink></span>
    </div>
  </header>
  <main><router-view /></main>
  <footer>rodape</footer>
</template>

<style>
@import "@/assets/style.css";
@import "@/assets/style.css";
#app {
  max-width: 1920px;
  margin: auto;
  height: 100vh;
  font-weight: normal;
}
header,
footer {
  height: 15%;
  display: flex;
  align-items: center;
  border: 1px black solid;
}
main {
  height: 70%;
}
</style>
