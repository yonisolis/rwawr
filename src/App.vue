<template>
  <div id="">
    <Navbar/>
    <Content/>
  

  </div>

</template>

<script>
import Navbar from './components/Navbar.vue'
import Content from './components/Content.vue'

export default {
  name: 'app',
  components: {
   
    Navbar,
    Content
  },
  data(){
   return{
     titulo:"proyecto vue cli"
   }

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
