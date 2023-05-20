<script>
   import AppHeader from "./components/AppHeader.vue";
   import AppMain from "./components/AppGetContents.vue";
   import AppComics from "./components/AppComics.vue";
   import AppIcon from "./components/AppIcon.vue"
   import AppFooter from "./components/AppFooter.vue";
   import AppCardComics from "./components/AppCardComics.vue";

   export default (await import("vue")).defineComponent({
   components: { AppHeader, AppComics, AppMain, AppIcon, AppFooter, AppCardComics },
      });
</script>

<template>
   <AppHeader></AppHeader>
   <AppMain></AppMain>
   <AppComics></AppComics>
   <AppIcon></AppIcon>
   <AppFooter></AppFooter>
</template>

<style lang="scss">
   @use "./assets/styles/general.scss" as *
</style>


