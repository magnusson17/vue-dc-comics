<template>
  <header>
      <div>
          <img src="../assets/img/dc-logo.png" alt="dc-logo">
      </div>
      <div>
          <ul>
              <li>characters</li>
              <li>comics</li>
              <li>movies</li>
              <li>tv</li>
              <li>games</li>
              <li>collectibles</li>
              <li>videos</li>
              <li>fans</li>
              <li>news</li>
              <li>shop</li>
              <li>characters</li>        
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
        text-transform: uppercase;
        margin: 0 20px;
        font-size: 0.5em;
        &:hover {
            color: blue;
        }
    }
}
</style>