<template>
  
  <HeaderPage/>
  <ColumnPage />
  <GridPractice />
</template>

<script>

import HeaderPage from './components/HeaderPage.vue';
//import HeaderPage from './components/header.vue'
import ColumnPage from './components/ColumnPage.vue'
import GridPractice from './components/GridPractice.vue'
export default {
  name: 'App',
  components: {
    HeaderPage,
    ColumnPage,
    GridPractice
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
