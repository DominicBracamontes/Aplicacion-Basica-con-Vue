<template>
  <v-app class="white-background">
    <AppHeader />

    <v-container>
      <v-row>
        <v-col cols="12" md="6">
          <TarjetaConImagen 
            titulo="HOTELES" 
            descripcion="Hoteles 5 estrellas" 
            imagen="https://picsum.photos/500/300" 
          />
        </v-col>
        <v-col cols="12" md="6">
          <TarjetaConImagen 
            titulo="RESTAURANTES" 
            descripcion="Restaurantes 5 estrellas" 
            imagen="https://picsum.photos/501/300" 
          />
        </v-col>
      </v-row>
    </v-container>

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
