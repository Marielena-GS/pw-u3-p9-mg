<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link :to="`/hola/${idEstudiante}`">Hola</router-link>|
    <router-link to="/pokemon">Pokemon</router-link> |
    <router-link to="/pregunta">Pregunta</router-link> |
    
    
  </nav>
  <input v-model="idEstudiante" type="text"> 
  <router-view/>
</template>

<script>
export default {
  data() {
    return {
      idEstudiante: null
    }
  }
  
}
</script>

<script>

</script>
