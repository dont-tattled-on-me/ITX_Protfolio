<template>
 <div id='app'>
   
   <nev />
   <home />
 </div>
</template>

<script>
import Home from './components/Home.vue'
import Nev from './components/Nev.vue'




export default {
  name: 'App',
  components:{
    Nev,
    Home,
    
  }
  
}
</script>

<style>
@import './assets/custom.css';

</style>
