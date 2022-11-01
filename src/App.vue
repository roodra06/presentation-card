<template>
  <div id="app">
    <nav>
      <strong><router-link to="/">Who I am?</router-link></strong> |
      <strong><router-link to="/about">My Likes</router-link></strong>
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image: linear-gradient(rgba(52, 237, 222, 0.55), rgba(9, 0, 236, 0.59))
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: rgba(9, 0, 236, 0.59);
    }
  }
}
</style>
