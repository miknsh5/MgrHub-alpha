

<template>
  <img alt="Vue logo" src="./assets/os-logo-300.png">
  <div id="app">
    <div id="nav">
      <router-link :to="{ name: 'Purpose' }">Purpose</router-link> |
      <router-link :to="{ name: 'About' }">Team</router-link> |
      <router-link :to="{ name: 'About' }">Ops</router-link> |
      <router-link :to="{ name: 'About' }">Analytics</router-link>
    </div>
    
    
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

h4 {
  font-size: 20px;
}
</style>
