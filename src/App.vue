<script>
    import AppHeader from "./components/AppHeader.vue";
    import AppMain from "./components/AppMain.Vue";
    import AppFooter from "./components/AppFooter.vue";

    export default (await import("vue")).defineComponent({
    components: { AppHeader, AppMain, AppFooter },
      });

</script>

<template>
   <AppHeader></AppHeader>
   <AppMain></AppMain>
   <AppFooter></AppFooter>
</template>

<style lang="scss">
   @use "./assets/styles/general.scss" as *

</style>
