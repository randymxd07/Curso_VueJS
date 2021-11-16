<template>

  <!-----------
      Imagen 
  ------------->
  <img alt="Vue logo" src="./assets/logo.png">
  
  <!-----------------------
      Componente Counter 
  ------------------------->
  <Counter :start="100" title="HOLA"/>

</template>

<script>

// Importo el componente Counter //
import Counter from './components/Counter.vue'

// Para exportar lo que esté aquí adentro //
export default {

  // Esto hace referencia a lo que se va a renderizar en el archivo main.js //
  name: 'App',

  // Para usar los componentes importados //
  components: {
    Counter // Componente Counter //
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
