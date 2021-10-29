<template>
  <Header />
  <Menu />
  <Dashboard />

</template>

<script>
import Header from './components/Layout/Header.vue'
import Menu from './components/Layout/Menu.vue'
import Dashboard from './components/Dashboard/Dashboard.vue'

export default {
  name: 'App',
  components: { 
    Header,
    Menu,
    Dashboard
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
</style>
