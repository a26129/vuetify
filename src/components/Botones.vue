<template>
  <v-row align="center" justify="space-around">
    <v-btn depressed>Fondo</v-btn>
    <v-btn text>No fondo</v-btn>
    <v-btn depressed disabled>Desabilitado</v-btn>
    <v-btn rounded>Redondeado</v-btn>
    <v-btn small>Pequeño</v-btn>
    <v-btn x-large>XL</v-btn>
  </v-row>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style>
.row {
  margin-top: 10px;
  margin-bottom: 10px;
  display: flex;
  justify-content: center;
}
</style>