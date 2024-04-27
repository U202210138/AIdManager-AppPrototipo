<script>
import AnalyticsChartDoughnut from "@/pages/analytics/components/analytics-chart/analytics-chart-pie.component.vue";

export default {
  name: "analytics-card-projects",
  components: {AnalyticsChartDoughnut}
}
</script>
<template>
  <h2>Clean Carpayo Beach</h2>
  <h3>Current projects</h3>
  <div class="flex">
    <pv-card class="card">
      <template #header>
        <p>Currents Status:</p>
      </template>
      <template #content>
        <div class="flex">
          <div style="margin-right: 10rem;">
            <p>Time</p>
            <p>Tasks</p>
            <p>Workload</p>
            <p>Progress</p>
            <p>Cost</p>
          </div>
          <div >
            <p>Tsssssssssss</p>
            <p>Tsssssssssssss</p>
            <p>W</p>
            <p>P</p>
            <p>C</p>
          </div>
        </div>
      </template>
    </pv-card>
    <pv-card class="card">
      <template #header>
        <p>Tasks:</p>
      </template>
      <template #content>
        <div class="flex">
         <analytics-chart-doughnut></analytics-chart-doughnut>
        </div>
      </template>
    </pv-card>
    <pv-card class="card">
      <template #header>
        <p>Currents Status:</p>
      </template>
      <template #content>
        <div class="flex">
          <div style="margin-right: 10rem;">
            <p>Time</p>
            <p>Tasks</p>
            <p>Workload</p>
            <p>Progress</p>
            <p>Cost</p>
          </div>
          <div >
            <p>Tsssssssssss</p>
            <p>Tsssssssssssss</p>
            <p>W</p>
            <p>P</p>
            <p>C</p>
          </div>
        </div>
      </template>
    </pv-card>
  </div>
  <br>
  <div class="flex">
    <pv-card class="card">
      <template #header>
        <p>Currents Status:</p>
      </template>
      <template #content>
        <div class="flex">
          <div style="margin-right: 10rem;">
            <p>Time</p>
            <p>Tasks</p>
            <p>Workload</p>
            <p>Progress</p>
            <p>Cost</p>
          </div>
          <div >
            <p>Tsssssssssss</p>
            <p>Tsssssssssssss</p>
            <p>W</p>
            <p>P</p>
            <p>C</p>
          </div>
        </div>
      </template>
    </pv-card>
    <pv-card class="card">
      <template #header>
        <p>Currents Status:</p>
      </template>
      <template #content>
        <div class="flex">
          <div style="margin-right: 10rem;">
            <p>Time</p>
            <p>Tasks</p>
            <p>Workload</p>
            <p>Progress</p>
            <p>Cost</p>
          </div>
          <div >
            <p>Tsssssssssss</p>
            <p>Tsssssssssssss</p>
            <p>W</p>
            <p>P</p>
            <p>C</p>
          </div>
        </div>
      </template>
    </pv-card>
    <pv-card class="card">
      <template #header>
        <p>Currents Status:</p>
      </template>
      <template #content>
        <div class="flex">
          <div style="margin-right: 10rem;">
            <p>Time</p>
            <p>Tasks</p>
            <p>Workload</p>
            <p>Progress</p>
            <p>Cost</p>
          </div>
          <div >
            <p>Tsssssssssss</p>
            <p>Tsssssssssssss</p>
            <p>W</p>
            <p>P</p>
            <p>C</p>
          </div>
        </div>
      </template>
    </pv-card>
  </div>
</template>

<style scoped>
.card{
  width: 25rem;
  height: 15rem;
  padding:30px;
  overflow: hidden;
  background-color: #E6F4E2;
  margin-right: 1rem;
}
.flex{
  display: flex;

}
</style>