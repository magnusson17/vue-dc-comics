<template>
  <div id="app">
    <HeaderComp/>
    <JumbotronComp/>
    <MainComp/>
    <FooterLinks/>
    <FooterJumbo/>
    <FooterSignUp/>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import FooterLinks from './components/footerComp/FooterLinks.vue'
import FooterJumbo from './components/footerComp/FooterJumbo.vue'
import FooterSignUp from './components/footerComp/FooterSignUp.vue'
import JumbotronComp from './components/JumbotronComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterLinks,
    FooterJumbo,
    FooterSignUp,
    JumbotronComp
  }
}
</script>

<style lang="scss">
body {
      margin: 0px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // padding: 0px;
  // margin: 0px;
  // margin-top: 60px;
}
</style>

<!-- Create un nuovo progetto utilizzando Vue CLI e definite i componenti necessari per strutturare il layout come da screenshot allegato.

Quando la struttura a macroblocchi è pronta, popolate le voci di menu dinamicamente usando i data del componente.
Per oggi diamo priorità alla struttura: quando è tutto bello solido, passiamo al Sass!

Bonus:
Creare un componente aggiuntivo per gestire la fascia azzurra con le icone -->
