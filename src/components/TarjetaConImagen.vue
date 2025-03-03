<script setup>
import { ref } from 'vue';

const imagen1 = ref('https://picsum.photos/500/300');
const imagen2 = ref('https://picsum.photos/501/300');
</script>

<template>
  <v-container>
    <v-row>
      <v-col cols="12" md="6">
        <v-card class="white-card shadow--none border-card">
          <v-img :src="imagen1" height="200px" cover></v-img>
          <v-card-title class="text-black">HOTELES</v-card-title>
          <v-card-text class="text-black">Hoteles 5 estrellas</v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" md="6">
        <v-card class="white-card shadow--none border-card">
          <v-img :src="imagen2" height="200px" cover></v-img>
          <v-card-title class="text-black">RESTAURANTES</v-card-title>
          <v-card-text class="text-black">Restaurantes 5 estrellas</v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.white-card {
  background-color: white !important;
  color: black !important;
  box-shadow: none;
}

.border-card {
  border: 2px solid #000;  
  border-radius: 8px; 
}
</style>
