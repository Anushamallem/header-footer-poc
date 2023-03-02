<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <page-header :appInfo="appInfo"/>
  <page-footer />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PageHeader from '@/components/PageHeader';
import PageFooter from './components/PageFooter.vue';
export default {
  name: 'App',
  data(){
    return{
      appInfo : {
        appTitle: 'Header poc',
        appDescription: 'it is working',
      }
    }

  },
  components: {
    HelloWorld,
    PageHeader,
    PageFooter
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
