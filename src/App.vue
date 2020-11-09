<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <div class="wrapper">
     <NavigationBar msg=""/>
     <div class="model-wrapper">
     <model1 msg="" index = "1"/>
     <model1 msg="" index = "2"/>
     </div>
     <!-- <model1 msg=""/> -->
     <!-- <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/>
     <model1 msg=""/> -->
     <rightHelp msg=""/>
     <BoxChange msg=""/>
     <img id = "model1pic" src="./assets/model1.png" alt = "model1">
  </div>
  
</template>

<script>
import NavigationBar from './components/NavigationBar.vue'
import model1 from './components/model1.vue'
import BoxChange from './components/BoxChange.vue'
import rightHelp from './components/rightHelp.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    NavigationBar,
    model1,
    BoxChange,
    rightHelp
  }
}
</script>

<style>

/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
.wrapper{
  width: 1400px;
  margin: 0 auto;
}
.model-wrapper::after{
  content: "";
  display: block; 
  clear: both;
}

</style>
