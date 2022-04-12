<template>
<div>
    <ul>
        <li><img src="../../assets/img/buy-comics-digital-comics.png" alt="dc-img">digital comics</li>
        <li><img src="../../assets/img/buy-comics-merchandise.png" alt="dc-img">dc merchandise</li>
        <li><img src="../../assets/img/buy-comics-subscriptions.png" alt="dc-img">subscription</li>
        <li><img src="../../assets/img/buy-comics-shop-locator.png" alt="dc-img">comic shop locator</li>
        <li><img src="../../assets/img/buy-dc-power-visa.svg" alt="dc-img">dc power visa</li>
    </ul>
</div>
</template>

<script>
export default {
  name: 'FooterLinks',
}
</script>

<style scoped lang="scss">
// mixin import
@import '../../style/mixin.scss';

div {
    background-color: blue;
    padding: 50px 0;
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