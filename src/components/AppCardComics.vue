<script>
export default {
    props: {
        urlImg: String,
        series: String,
        }
    }
</script>

<template>
   <div class="card">
    <img :src="urlImg" :alt="series">
    <h5> {{ series }} </h5>
   </div>
</template>

<style lang="scss" scoped>
   @use "../assets/styles/general.scss" as *;

   .card {
    width: calc((100% - 5rem) / 6 );
    &:hover {
        cursor: pointer;
        }
    }

   img {
    width: 100%;
    aspect-ratio: 1 / 1;
   }

   h5 {
    color: grey;
    &:hover {
        color: white;
        }
    }
</style>
