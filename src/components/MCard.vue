<template>
  <v-container class="fill-height" fluid>
    <v-row align="center" justify="center">
      <v-card class="mx-auto" min-width="444">
        <v-card-text>
          <p class="display-1 text--primary">Marks</p>
          <div class="text--primary">
            <v-text-field label="Search marks..." hide-details="auto"></v-text-field>
          </div>
        </v-card-text>
        <v-card-actions>
          <v-btn text color="quinary accent-4">...</v-btn>
        </v-card-actions>
      </v-card>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "MCard",

  data: () => ({})
});
</script>
