<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <nav class="navbar">
    <NavLink url="/" text="Acceuil" />
    <NavLink url="/about" text="À propos" />
			<NavLink url="/contact" text="Contact" />
  </nav>
  <HelloWorld msg="Welcome to my first vue cli app"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavLink from './components/NavLink.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavLink
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.navbar a{
  margin-right: 10px;
}
</style>
