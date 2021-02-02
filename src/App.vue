<template>
  <v-app>
    <v-app-bar app color="teal darken-2" dark>
      <h1>Vue Meme Forum</h1>
      <v-spacer></v-spacer>
      <router-link to="/"> Home </router-link>
      <router-link to="/create"> Create </router-link>
      <router-link to="/feed"> Memes </router-link>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<style scoped>
a {
  text-decoration: none;
}
.router-link-active .v-btn {
  color: rgb(255, 200, 100);
}
</style>
