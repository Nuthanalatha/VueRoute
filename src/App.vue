<template>
  <nav-comp />
  <!-- <home-comp/>
<office-comp/> -->
  <router-view></router-view>
</template>

<script>
import NavComp from "./components/NavComp.vue";
// import OfficeComp from './components/OfficeComp.vue';
// import HomeComp from './HomeComp.vue';

export default {
  name: "App",
  components: {
    NavComp,
    // OfficeComp,
    // HomeComp,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
