<template>
  <header>
      <div>
          <img src="../assets/img/dc-logo.png" alt="dc-logo">
      </div>
      <div>
          <ul>
              <li>CHARACTERS</li>
              <li>COMICS</li>
              <li>MOVIES</li>
              <li>TV</li>
              <li>GAMES</li>
              <li>COLLECTIBLES</li>
              <li>VIDEOS</li>
              <li>FANS</li>
              <li>NEWS</li>
              <li>SHOP</li>
          </ul>
      </div>
  </header>
</template>

<script>
export default {
  name: 'HeaderComp',
}
</script>

<style scoped lang="scss">
header {
    display: flex;
    align-items: center;
    justify-content: space-around;
}
ul {
    list-style: none;
    display: flex;
    li {
        text-align: left;
        margin: 0 20px;
        font-size: 0.5em;
        &:hover {
            color: blue;
        }
    }
}
</style>