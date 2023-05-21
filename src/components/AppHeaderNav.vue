<script>
    export default {
    props: {
            navString: String,
            link: String,
        }
}
</script>

<template>
    <a :href="link"> {{ navString }} </a>
</template>

<style lang="scss" scoped>
    a {
        padding: .6rem;
        text-decoration: none;
        color: black;
        &:hover {
            cursor: pointer;
            color: blue;
        }
    }
</style>