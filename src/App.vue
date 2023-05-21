<script>
   import AppHeader from "./components/AppHeader.vue";
   import AppComics from "./components/AppComics.vue";
   import AppCardComics from "./components/AppCardComics.vue";
   import AppIcon from "./components/AppIcon.vue"
   import AppFooter from "./components/AppFooter.vue";

   export default (await import("vue")).defineComponent({
   components: { AppHeader, AppComics, AppCardComics, AppIcon, AppFooter, },
      });
</script>

<template>
   <AppHeader></AppHeader>
   <AppComics></AppComics>
   <AppIcon></AppIcon>
   <AppFooter></AppFooter>
</template>

<style lang="scss">
   @use "./assets/styles/general.scss" as *
</style>


