<template>
    <div class="container">
        <div class="info">
            <div class="img">
                <img src="../assets/buy-comics-digital-comics.png" alt="">
            </div>
            <span>DIGITAL COMICS</span>
        </div>
        <div class="info">
            <div class="img">
                <img src="../assets/buy-comics-merchandise.png" alt="">
            </div>
            <span>DC MERCHANDISE</span>
        </div>
        <div class="info">
            <div class="img">
                <img src="../assets/buy-comics-subscriptions.png" alt="">
            </div>
            <span>SUBSCRITION</span>
        </div>
        <div class="info">
            <div class="img">
                <img src="../assets/buy-comics-shop-locator.png" alt="">
            </div>
            <span>COMIC SHOP LOCATION</span>
        </div>
        <div class="info">
            <div class="img">
                <img src="../assets/buy-dc-power-visa.svg" alt="">
            </div>
            <span>DC POWER VISA</span>
        </div>
    </div>
</template>

<script>

</script>

<style lang="scss" scoped>
    img{
        width: 60px;
    }
    span{
        color: white;
    }
    .container{
        display: flex;
        justify-content: space-around;
        background-color: #0282F9;
        .info{
            padding: 20px;
            display: flex;
            align-items: center;
        }
        .img{
            padding: 10px;
        }

        
    }
</style>