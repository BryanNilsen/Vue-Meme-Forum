<template>
  <v-app>
    <v-app-bar app color="teal darken-2" dark>
      <h1>Vue Meme Forum</h1>
      <v-spacer></v-spacer>
      <router-link to="/create"> Create </router-link>
      |
      <router-link to="/feed"> Memes </router-link>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
