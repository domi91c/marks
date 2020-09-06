<template>
  <v-app>
    <v-main>
      <m-card></m-card>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import Vuetify from "vuetify";
import "vuetify/dist/vuetify.min.css";
import MCard from "@/components/MCard.vue";

Vue.use(Vuetify);

export default Vue.extend({
  name: "App",
  components: { MCard }
});
</script>
