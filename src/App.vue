<template>

   <MainCard/>
    
   <ReposiTory/>
</template>

<script>
import MainCard from './components/MainCard.vue'
import ReposiTory from './components/ReposiTory'
export default {
  name: 'App',
  components: {
    MainCard,
    ReposiTory,
  
}
}
</script>

<style>
*
{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #17202A ;

 
}
</style>
