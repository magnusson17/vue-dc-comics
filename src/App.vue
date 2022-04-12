<template>
  <div id="app">
    <HeaderComp></HeaderComp>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // margin-top: 60px;
}
</style>

<!-- Create un nuovo progetto utilizzando Vue CLI e definite i componenti necessari per strutturare il layout come da screenshot allegato.

Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente.
Per oggi diamo priorità alla struttura: quando è tutto bello solido, passiamo al Sass!

Bonus:
Creare un componente aggiuntivo per gestire la fascia azzurra con le icone -->
