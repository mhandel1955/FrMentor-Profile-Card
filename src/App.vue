<template>
  <app-bkgrnd><profile-card /></app-bkgrnd>
</template>

<script>
import AppBkgrnd from "./components/AppBkgrnd.vue";
import ProfileCard from "./components/ProfileCard.vue";

export default {
  name: "App",
  components: {
    AppBkgrnd,
    ProfileCard,
  },
};
</script>

<style>
#app {
  margin: 0;
}
</style>
