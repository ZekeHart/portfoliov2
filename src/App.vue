<template>  
  <div id="app">    
    <img alt="Zeke head shot" class="headShot" src="./assets/HeadShotEdited.jpeg">    
    <component1 msg="Zeke's Portfolio"/>  
  </div>
</template>
 

<script>

import HelloWorld from './components/HelloWorld.vue'
import component1 from './components/component1.vue'

export default {
  name: 'app',
  components: {
    component1
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

body {
    background: linear-gradient(45deg, #4a026b, #0d26b3, #1a84db, #0d26b3, #4a026b);
    background-size: 300% 200%;
    animation: AnimationName 10s ease infinite;
}

@keyframes AnimationName { 
    0%{background-position:0% 50%}
    50%{background-position:100% 50%}
    100%{background-position:0% 50%}
}

.headShot {
  border-radius: 10%;
  max-width: 300px;
}
</style>
