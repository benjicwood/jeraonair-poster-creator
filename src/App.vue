<template>
  <JeraOnAirPoster />
</template>

<script>
import JeraOnAirPoster from "./components/JeraOnAirPoster/JeraOnAirPoster.vue";

export default {
  name: "App",
  components: {
    JeraOnAirPoster,
  },
};
</script>

<style>
.app {
  width: 100vw;
  min-height: 100vh;
  display: flex;
  /* justify-content: center; */
  align-items: center;
  background-color: black;
  background-size: contain;
  background-repeat: no-repeat;
  background-position: top center;
  padding: 0.5rem;
  box-sizing: border-box;
}
/* Make the app fill the viewport */
</style>
