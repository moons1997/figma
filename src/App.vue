<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="c-wrapper">
    <header></header>
    <main>
      <div class="c-container">
        <div class="sidebar"></div>
        <div class="main"></div>
      </div>
    </main>
    <footer></footer>
  </div>

  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>
  <div class="aaaaaaa">

    <RouterView />
  </div> -->
</template>

<style scoped></style>
