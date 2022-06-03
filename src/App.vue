
<template>
  
      
  
  <div class="form">  
    <registerForm/>
  </div>
</template>

<script>
import registerForm from './components/registerForm.vue'

export default{
  name: 'App',
  components:{registerForm}
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
