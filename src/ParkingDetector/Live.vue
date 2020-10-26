<template>
  <b-card header="实时监控">
    <!-- <b-img :src="require('../assets/360x240.jpg')" fluid-grow /> -->
    <b-img :src="'http://'+host+'/camera/live'" fluid-grow />
  </b-card>
</template>

<script>
export default {
  name: "live",
  props: {
    host: String,
  }
};
</script>

<style>
</style>