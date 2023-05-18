<script>

</script>

<template>
    <div class="footer">
        <div class="footer-top">
            <div class="link">
                <ul>
                    <li class="first">DC COMICS</li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>

                <ul>
                    <li class="first">DC</li>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>

                <ul>
                    <li class="first">SITES</li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Vise</li>
                </ul>
                <ul class="shop">
                    <li class="first">SHOP</li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <div class="logo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="footer-bottom">
            <button> <span>SIGN-UP NOW!</span></button>
            <div class="social">
                <span>FOLLOW US</span>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>

span {
    color: white;
}

li {
    list-style: none;
    font-size: .9rem;
    color: grey;
}

button {
    background-color: #303030;
    padding: .5rem;
    border-color: blue;
    &:hover {
        cursor: pointer;
    }
}

.first {
    color: white;
    font-size: 1rem;
    padding-top: 2rem;
    padding-bottom: .8rem;
}

.footer {
    height: 55vh;
    .footer-top {
        display: flex;
        height: 45vh;
        background-image: url("../assets/img/footer-bg.jpg");
        .link {
            display: flex;
            justify-content: center;
            align-items: top;
            flex-wrap: wrap;
            gap: 2rem;
            color: white;
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
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 10vh;
        background-color: #303030;
        .social {
            display: flex;
            align-items: center;
            gap: .5rem;
        }
    }
}

</style>
