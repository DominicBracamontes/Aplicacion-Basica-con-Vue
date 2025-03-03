<template>
  <v-app class="white-background">
    <AppHeader />
    <TarjetaConImagen />
    <TablaDeDatos />
    <AppFooter />
  </v-app>
</template>

<script setup>
import AppHeader from './components/AppHeader.vue';
import TarjetaConImagen from './components/TarjetaConImagen.vue';
import TablaDeDatos from './components/TablaDeDatos.vue';
import AppFooter from './components/AppFooter.vue';
</script>

<style>
.white-background {
  background-color: white !important;
}

.v-application {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.v-main {
  flex-grow: 1;
}
</style>
