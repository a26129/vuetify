<template>
  <v-app>
    <v-carousel class="caruusel">
      <v-carousel-item v-for="color in colors" :key="color">
        <v-sheet :color="color" height="100%" tile>
          <v-row class="fill-height" align="center" justify="center">
            <div class="text-h2">{{ color }}</div>
          </v-row>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    colors: ["red", "orange", "yellow", "green", "blue", "indigo", "purple"],
  }),
};
</script>

<style>
.v-application--wrap{
  min-height: 0 ;
}
.caruusel {
  width: 90%;
  margin: 0 auto;
}
</style>