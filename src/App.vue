<template>
  <div>
    <app-header></app-header>
    <app-footer></app-footer>
  </div>
  <!--
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <router-link to="/top">トップページ</router-link>
  </div>
  -->
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'
export default {
  name: 'App',
  components:{
    'app-header': Header,
    'app-footer': Footer
  }
}


</script>

<style>
/*
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*/

html {
  height:100%;
  background: linear-gradient(#05FBFF, #1E00FF);
}
</style>
