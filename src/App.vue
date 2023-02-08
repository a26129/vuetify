<template>
    <v-main>
      <Botones></Botones>
      <Carrusel></Carrusel>
      <Carta></Carta>
      <Formulario></Formulario>
      <Paginacion></Paginacion>
      <Pie></Pie>
    </v-main>
</template>

<script>
import Carrusel from './components/Carrusel'
import Pie from './components/Pie'
import Botones from './components/Botones'
import Carta from './components/Carta'
import Paginacion from './components/Paginacion'
import Formulario from './components/Formulario'
export default {
  name: 'App',

  components: {
    Pie,
    Botones,
    Carrusel,
    Carta,
    Paginacion,
    Formulario
  },

  data: () => ({
    //
  }),
};
</script>