<script>

</script>

<template>
    <div class="footer">
        <div class="footer-top">
            <div class="link"></div>
            <div class="logo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="footer-bottom"></div>
    </div>
</template>

<style lang="scss" scoped>

.footer {
    height: 55vh;
    .footer-top {
        display: flex;
        height: 45vh;
        background-image: url("../assets/img/footer-bg.jpg");
        .link {
            width: 60%;
            height: 45vh;
        }
        .logo {
            width: 40%;
        }
        .logo img {
            width: 50%;
            object-fit: contain;
            object-position: center;
        }
    }
    .footer-bottom {
        height: 10vh;
        background-color: #303030;
    }
}

</style>
