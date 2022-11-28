<template>
  <div class="container">
    <div class="sign-up">
      <p>SIGN-UP NOW!</p>
    </div>

    <div class="follow">
      <span>FOLLOW US</span>
      <img
        src="../assets/footer-facebook.png"
        alt=""
      >
      <img
        src="../assets/footer-twitter.png"
        alt=""
      >
      <img
        src="../assets/footer-youtube.png"
        alt=""
      >
      <img
        src="../assets/footer-pinterest.png"
        alt=""
      >
      <img
        src="../assets/footer-periscope.png"
        alt=""
      >
    </div>
  </div>
</template>

<script>

</script>

<style lang="scss" scoped>
    img{
        padding: 10px;
    }
    .container{
        display: flex;
        align-items: center;
        justify-content: space-between;
        background-color: #303030;
    }
    .sign-up{
        padding: 3px;
        margin-left: 50px;
        color: white;
        border: solid 3px #0282F9;
    }
    .follow{
        display: flex;
        align-items: center;
        span{
            margin-right: 5px;
            color: #0282F9;
            font-weight: bold;
        }
    }
</style>
