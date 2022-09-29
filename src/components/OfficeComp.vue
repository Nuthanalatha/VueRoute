<template>
  <h1>I am Office Component</h1>
  <button @click="goToHome">Go To Home</button>
</template>

<script>
export default {
  methods: {
    //to navigate programatically
    goToHome() {
      // console.log("executed");
      this.$router.push("/");
      // this.$router.back();
      // this.$router.forward();
    },
  },
};
</script>

<style></style>
