<template>
  <app-bkgrnd><profile-card class="child-root" /></app-bkgrnd>
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
.child-root {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
