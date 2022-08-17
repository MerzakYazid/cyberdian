<template>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Vue app</title>
  </head>
  <body>
    <NavBar/>
    <DashBoard/>
    <CAlert/>
  </body>
  
</template>

<script>
import NavBar from './components/NavBar.vue'
import DashBoard from './components/DashBoard.vue'
import { CAlert } from '@coreui/vue';
export default {
  name: 'App',
  components: {
    NavBar,
    DashBoard,
    CAlert
  }
}
</script>

<style>
* { 
  margin: 0;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: rgba(235,237,239,255);
  display: flex;
  
}
</style>
