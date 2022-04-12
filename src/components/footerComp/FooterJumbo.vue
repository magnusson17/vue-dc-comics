<template>
<div class="main_container">
    <div class="div_container">
        <div class="ul_container">
            <ul>dc comics
                <li>characters</li>
                <li>comics</li>
                <li>movies</li>
                <li>tv</li>
                <li>games</li>
                <li>videos</li>
                <li>news</li>
            </ul>
            <ul>shop
                <li>shop DC</li>
                <li>shop DC collectibles</li>
            </ul>
        </div>
        <div class="ul_container">
            <ul>dc
                <li>terms of use</li>
                <li>privacy policy</li>
                <li>ad choices</li>
                <li>advertising</li>
                <li>jobs</li>
                <li>subscriptions</li>
                <li>talent workshops</li>
                <li>CPSC certificates</li>
                <li>ratings</li>
                <li>shop help</li>
                <li>contact us</li>
            </ul>
        </div>
        <div class="ul_container">
            <ul>sites
                <li>DC</li>
                <li>MAD magazine</li>
                <li>kids</li>
                <li>univers</li>
                <li>power visa</li>
            </ul>
        </div>
    </div>

    <div class="div_container">
        <img src="../../assets/img/dc-logo-bg.png" alt="dc-logo">
    </div>
</div>
</template>

<script>
export default {
  name: 'FooterJumbo',
}
</script>

<style scoped lang="scss">

@import '../../style/mixin.scss';

.main_container {
    display: flex;
    background-image: url("../../assets/img/footer-bg.jpg");
    height: 30vh;
}
.div_container {
    @include displayFlex(center, center);
    width: 50%;
}
.ul_container {
    @include displayFlex(center, start);
    flex-direction: column;
}
ul {
    @include ulReset;
    color: white;
    text-transform: uppercase;
    text-align: left;
    li {
        text-transform: capitalize;
        color: white;
        font-size: 0.7em;
        text-align: left;
    }
}

img {
    height: 120%;
}
</style>