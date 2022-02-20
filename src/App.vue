<script setup lang="ts">
import QRCode from "./components/QRCode.vue";
</script>

<template>
  <main>
    <QRCode />
  </main>
</template>

<style>
@import "./assets/base.css";

#app {
  max-width: 1280px;
  height: 100vh;

  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
