<script>

</script>

<template>
    <div class="nav">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="voices">
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
    </div>
</template>

<style lang="scss" scoped>

li {
    list-style: none;
    &:hover {
            cursor: pointer;
            color: blue;
        }
}

.nav {
    height: 10vh;
    display: flex;
    justify-content: space-around;
    align-items: center;
    .logo img{
        width: 50%;
    }
    .voices ul {
        display: flex;
        font-size: .8rem;
        gap: 1rem;

    }
}
</style>
