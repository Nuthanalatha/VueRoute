<template>
  <h1>I am Home Component</h1>
  <button @click="goToOffice">Go To Office</button>
</template>

<script>
export default {
  methods: {
    goToOffice() {
      // console.log("executed");
      this.$router.push("/office");
    },
  },
};
</script>

<style></style>
