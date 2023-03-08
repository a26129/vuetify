<template>
    <v-main>
      <Tarjeta></Tarjeta>
    </v-main>
</template>

<script>
import Tarjeta from './components/Carta'
/*
import Carrusel from './components/Carrusel'
import Pie from './components/Pie'
import Botones from './components/Botones'

import Paginacion from './components/Paginacion'
import Formulario from './components/Formulario'*/
export default {
  name: 'App',

  components: {
  /*  Pie,
    Botones,
    Carrusel,*/
    Tarjeta/*,
    Paginacion,
    Formulario*/
  },

  data: () => ({
    //
  }),
};
</script>