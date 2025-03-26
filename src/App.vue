<script setup>
import { ref } from 'vue'

const drawer = ref(false)
</script>

<template>
  <div>
    <v-app>
      <v-navigation-drawer v-model="drawer" app>
      </v-navigation-drawer>

      <v-app-bar app>
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>

        <v-toolbar-title>Application</v-toolbar-title>
      </v-app-bar>
    </v-app>
  </div>
</template>

<style lang="css" scoped></style>