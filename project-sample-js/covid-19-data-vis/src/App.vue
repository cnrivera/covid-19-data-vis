<template>
  <div id="app container is-fluid">
    <CaseDistributionChart />
  </div>
</template>

<script>
import CaseDistributionChart from './components/CaseDistributionChart.vue'

export default {
  name: 'App',
  components: {
    CaseDistributionChart,
  }
}
</script>

<style>
@import "../node_modules/bulma/css/bulma.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
