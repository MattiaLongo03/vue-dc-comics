<template>
  <header>
    <div class="logo">
      <img
        src="../assets/dc-logo.png"
        alt=""
      >
    </div>
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
  </header>
</template>

<script>

</script>

<style lang="scss" scoped>
  header{
    display: flex;
    justify-content: space-between;
    .logo{
      margin-left: 50px;
    }
    ul{
      margin-right: 200px;
      display: flex;
      list-style: none;
      align-items: center;
    }
    li{
      padding-right: 30px;
      font-weight: bold;
    }
  }
</style>
