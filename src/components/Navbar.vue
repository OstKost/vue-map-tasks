<template>
  <v-app-bar color="#2b7294" dark>
    <v-app-bar-nav-icon></v-app-bar-nav-icon>

    <v-toolbar-title>
      <router-link to="/" class="title">
        Task map
      </router-link>
    </v-toolbar-title>

    <v-spacer></v-spacer>

    <v-btn icon>
      <v-icon>mdi-dots-vertical</v-icon>
    </v-btn>

    <template v-slot:extension>
      <v-tabs align-with-title>
        <v-tab to="/">
          Главная
        </v-tab>
        <v-tab to="/statement">
          Журнал
        </v-tab>
        <v-tab to="/map">
          Карта
        </v-tab>
      </v-tabs>
    </template>
  </v-app-bar>
</template>

<style lang="scss" scoped>
.title {
  text-decoration: none;
  text-transform: uppercase;
  font-weight: bold;
  color: white;
}
</style>
