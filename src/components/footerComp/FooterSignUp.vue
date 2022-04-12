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
header {
    display: flex;
    align-items: center;
    justify-content: space-around;
}

button {
    text-transform: uppercase;
}
ul {
    list-style: none;
    display: flex;
    li {
        text-transform: uppercase;
        margin: 0 20px;
        font-size: 0.5em;
        &:hover {
            color: blue;
        }
    }
}
</style>