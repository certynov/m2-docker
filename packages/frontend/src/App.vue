<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <v-toolbar-title>TP Docker multi-conteneur</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class App extends Vue {}
</script>
