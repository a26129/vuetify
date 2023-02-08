<template>
    <v-form>
      <v-text-field v-model="nombreFormulario" label="Nombre"></v-text-field>
      <v-text-field v-model="apellidoFormulario" label="Apellido"></v-text-field>
      <v-text-field v-model="emailFormulario" label="email"></v-text-field>
    </v-form>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    nombreFormulario: "",
    apellidoFormulario: "",
    emailFormulario: "",
  }),
}
</script>

<style>
form{
    width: 50%;
    margin: 0 auto;
}
</style>