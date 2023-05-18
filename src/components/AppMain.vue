<script>

</script>

<template>
    <div class="main">
        <div class="content">
            <span> Content goes here </span>
        </div>
        <div class="images">
            <div class="mini-card">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span> 
            </div>
            <div class="mini-card">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div class="mini-card">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="mini-card">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="mini-card">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>

.main {
    height: 35vh;
    .content {
        color: white;
        background-color: black;
        height: 15vh;
        display: flex;
        align-items: center;
         span {
            font-size: 1.5rem;
            margin-left: 200px;
        }
    }
    .images {
        color: white;
        background-color: #0282F9;
        height: 20vh;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 3rem;
        img {
            width: 50px;
            height: 60px;
        }
        .mini-card {
            display: flex;
            align-items: center;
            span {
                padding-left: 1rem;
            }
        }
        
    }
}   

</style>