<template>
  <v-app>
    <navigation-drawer />

    <default-bar />

    <default-view />
  </v-app>
</template>

<script lang="ts" setup>
  import DefaultBar from './AppBar.vue'
  import DefaultView from './View.vue'
  import NavigationDrawer from './Drawer.vue'
</script>
