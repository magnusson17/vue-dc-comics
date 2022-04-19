<template>
<div>
    <ul>
        <li v-for="(element, index) in listaLink" :key="index">
            <img :src="require(`../../assets/img/${element.img}`)" alt="dc-img">
            <span>{{element.title}}</span>
        </li>
    </ul>
</div>
</template>

<script>
export default {
  name: 'FooterLinks',

  data() {
      return {
          listaLink: [
              {
                  title: 'digital comics',
                  img: 'buy-comics-digital-comics.png',
              },
              {
                  title: 'dc merchandise',
                  img: 'buy-comics-merchandise.png',
              },
              {
                  title: 'subscription',
                  img: 'buy-comics-subscriptions.png',
              },
              {
                  title: 'comic shop locator',
                  img: 'buy-comics-shop-locator.png',
              },
              {
                  title: 'dc power visa',
                  img: 'buy-dc-power-visa.svg',
              },
          ]
      }
  }
}
</script>

<style scoped lang="scss">
// mixin import
@import '../../style/mixin.scss';

div {
    background-color: blue;
    padding: 50px 0;
    // position: relative;
    // top: 50px;
}

ul {
    @include displayFlex(center, center);
    @include ulReset;
    li {
        @include displayFlex(center, center);
        text-transform: uppercase;
        color: white;
        font-size: 0.7em;
        margin: 0 20px;
        cursor: pointer;
        img {
            height: 50px;
        }
    }
}
</style>