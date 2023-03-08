<template>
  <v-card>
    <v-card style="margin: 0 auto;width: 50%;">
      <v-img :src=imagen aspect-ratio="2.75"></v-img>
      <v-card-title primary-title>
        <div>
          <h3 class="headline mb-0">{{titulo}}</h3>//
          <div>{{ card_text }}</div>
        </div>
      </v-card-title>
      <v-card-actions>
        <v-btn flat>texto</v-btn>
      </v-card-actions>
    </v-card>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      titulo: "titulo ejemplo",
      card_text:
        "Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo Texto ejemplo",
      imagen:"https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Solid_red.svg/512px-Solid_red.svg.png"
    };
  },
};
</script>

<style>

</style>