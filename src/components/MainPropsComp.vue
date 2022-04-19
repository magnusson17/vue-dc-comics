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
  //@include displayFlex(center, center);
  display: inline-block;
}

.box {
    width: 200px;
    height: 200px;
    color: white;
    @include displayFlex(center, center);
    flex-direction: column;
}

</style>