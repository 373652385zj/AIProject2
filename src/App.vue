<template>
  <div>
    <b-navbar variant="info" type="dark" class="mb-3">
      <b-navbar-brand class="ml-5">智能分析盒子</b-navbar-brand>
      <b-navbar-nav class="ml-auto">
        <b-nav-item><b-icon-person-fill /></b-nav-item>
        <b-nav-item><b-icon-box-arrow-right /></b-nav-item>
      </b-navbar-nav>
    </b-navbar>
    <b-container fluid>
      <b-row class="justify-content-md-center">
        <b-col md="2" class="border-right">
          <b-button block size="lg" variant="outline-secondary">假装</b-button>
          <b-button block size="lg" variant="outline-secondary">这里</b-button>
          <b-button block size="lg" variant="outline-secondary">有一个</b-button>
          <b-button block size="lg" variant="outline-secondary">工具栏</b-button>
        </b-col>
        <b-col md="10">
          <parking-detector />
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import ParkingDetector from './ParkingDetector/ParkingDetector'

export default {
  name: 'App',
  components: {
    ParkingDetector
  }
}
</script>

<style>
</style>
