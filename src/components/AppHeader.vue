<script>
    import AppHeaderNav from './AppHeaderNav.vue';

export default {
    data() {
        return {
                navArray: [
            {
                string: 'CHARACTERS',
                link: '#'
            },
            {
                string: 'COMICS',
                link: '#'
            },
            {
                string: 'MOVIE',
                link: '#'
            },
            {
                string: 'TV',
                link: '#'
            },
            {
                string: 'GAMES',
                link: '#'
            },
            {
                string: 'COLLECTIBLES',
                link: '#'
            },
            {
                string: 'VIDEOS',
                link: '#'
            },
            {
                string: 'FANS',
                link: '#'
            },
            {
                string: 'NEWS',
                link: '#'
            },
            {
                string: 'SHOP',
                link: '#'
            }
        ]
            }
    },
            components: {
                AppHeaderNav
                }
    }
</script>

<template>
    <div class="nav">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="voices">
            <AppHeaderNav v-for="navString in navArray" :navString="navString.string" :link="navString.link"/>
        </div>
    </div>
</template>

<style lang="scss" scoped>
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
