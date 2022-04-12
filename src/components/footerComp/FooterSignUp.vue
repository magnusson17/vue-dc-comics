<template>
  <header>
      <div>
          <button>sign up now!</button>
      </div>
      <div>
          <ul>
              <li>follow us</li>
              <li><img src="../../assets/img/footer-facebook.png" alt=""></li>
              <li><img src="../../assets/img/footer-periscope.png" alt=""></li>
              <li><img src="../../assets/img/footer-pinterest.png" alt=""></li>
              <li><img src="../../assets/img/footer-twitter.png" alt=""></li>
              <li><img src="../../assets/img/footer-youtube.png" alt=""></li>       
          </ul>
      </div>
  </header>
</template>

<script>
export default {
  name: 'FooterSignUp',
}
</script>

<style scoped lang="scss">

@import '../../style/mixin.scss';

header {
    @include displayFlex(space-around, center);
    background-color: rgb(54, 52, 52);
}

button {
    text-transform: uppercase;
    border: 2px solid blue;
    background-color: transparent;
    padding: 10px;
    color: white;
}
ul {
    @include displayFlex(center, center);
    list-style: none;
    li {
        text-transform: uppercase;
        margin: 0 10px;
        font-size: 0.7em;
        color: blue;
    }
}
</style>