<template>
  <v-app>
    <v-app-bar absolute>
      <v-toolbar-title>タイトル</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon class="hidden-xs-only">
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
    </v-app-bar>
    <v-content>
      <router-view/>
    </v-content>
    <v-footer>Copyright © 2020 Company Co.,Ltd. All Rights Reserved.</v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
</style>
