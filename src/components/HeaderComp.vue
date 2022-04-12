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
    justify-content: space-around;
    align-items: center;
    height: 20vh;
}

div {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
}

ul {
    display: flex;
    height: 100%;
    list-style: none;
    // azzerare il default style
    padding-inline-start: 0px;
    margin-block-start: 0px;
    margin-block-end: 0px;
    li {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
        text-transform: uppercase;
        margin: 0 20px;
        font-size: 0.7em;
        cursor: pointer;
        &:hover {
            color: blue;
            box-shadow: 0px 2px blue;
        }
    }
}
</style>