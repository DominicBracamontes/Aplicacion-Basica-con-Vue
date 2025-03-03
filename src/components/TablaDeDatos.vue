<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" md="10">
        <v-table density="comfortable" class="bordered-table">
          <thead>
            <tr class="bg-black text-white">
              <th class="text-center"></th>
              <th class="text-center">Lunes</th>
              <th class="text-center">Martes</th>
              <th class="text-center">Miércoles</th>
              <th class="text-center">Jueves</th>
              <th class="text-center">Viernes</th>
              <th class="text-center">Sábado</th>
              <th class="text-center">Domingo</th>
            </tr>
          </thead>
          <tbody>
            <tr class="bg-grey lighten-3">
              <td class="text-center">Hotel1</td>
              <td class="text-center"></td>
              <td class="text-center">X</td>
              <td class="text-center">X</td>
              <td class="text-center">X</td>
              <td class="text-center">X</td>
              <td class="text-center"></td>
              <td class="text-center"></td>
            </tr>
            <tr class="bg-white">
              <td class="text-center">Hotel2</td>
              <td class="text-center">X</td>
              <td class="text-center">X</td>
              <td class="text-center">X</td>
              <td class="text-center"></td>
              <td class="text-center"></td>
              <td class="text-center"></td>
              <td class="text-center"></td>
            </tr>
            <tr class="bg-grey lighten-3">
              <td class="text-center">Hotel3</td>
              <td class="text-center"></td>
              <td class="text-center"></td>
              <td class="text-center"></td>
              <td class="text-center">X</td>
              <td class="text-center">X</td>
              <td class="text-center">X</td>
              <td class="text-center">X</td>
            </tr>
          </tbody>
        </v-table>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.bordered-table {
  border-collapse: collapse;
  width: 100%;
}

.bordered-table th,
.bordered-table td {
  border: 1px solid black;
  padding: 10px;
  text-align: center;
}
</style>
