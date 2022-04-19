<template>
  <div class="container">
    <div class="box">
        <img :src="src" alt="">
        <h3>{{nome}}</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainPropsComp',
  props: {
      src: String,
      nome: String,
  } 

}
</script>

<style scoped lang="scss">

@import '../style/mixin.scss';

.container {
    display: flex;
    flex-basis: calc((100% / 6) - 10px);
    .box {
        // aspect-ratio: 1;
        padding: 10px;
        color: white;
        @include displayFlex(center, center);
        flex-direction: column;
        text-align: left;
    }
}

</style>