<template>
  <v-container>
    <v-layout flex align-center justify-center>
      <v-flex md8 style="height: 40em">
        <v-card elevation="7" min-height="40em">
          <v-card-title class="headline">
            ARQUITECTURA
          </v-card-title>
          <v-card-text>
            <organigrama style="height: 40em"/>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script lang="ts">
  import Vue from 'vue';
  import Organigrama from "@/components/Organigrama.vue";
  export default Vue.extend({
      name: "Arquitectura",
      components: {
          Organigrama
      }
  })
</script>

<style scoped>

</style>