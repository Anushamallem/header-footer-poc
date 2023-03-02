<template>
    <div class="hello">
      <h1>{{ appInfo.appTitle }}</h1><br>
      <h1>{{ appInfo.appDescription }}</h1><br>
    </div>
  </template>
  
  <script>
  export default {
    name: 'PageHeader',
    props: {
      msg: String,
      appInfo:Object
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  
  </style>
  