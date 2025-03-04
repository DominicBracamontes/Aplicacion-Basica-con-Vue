<script setup>
defineProps({
  titulo: String,
  descripcion: String,
  imagen: String
});
</script>

<template>
  <v-card class="white-card shadow--none border-card">
    <v-img :src="imagen" height="200px" cover></v-img>
    <v-card-title class="text-black">{{ titulo }}</v-card-title>
    <v-card-text class="text-black">{{ descripcion }}</v-card-text>
  </v-card>
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
