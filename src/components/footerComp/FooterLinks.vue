<template>
<div>
    <ul>
        <li><img src="../../assets/img/buy-comics-digital-comics.png" alt="dc-img"> digital comics</li>
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
div {
    background-color: blue;
}
ul {
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
    li {
        text-transform: uppercase;
        margin: 0 20px;
        color: white;
        display: flex;
        align-items: center;
        font-size: 0.5em;
    }
}
</style>