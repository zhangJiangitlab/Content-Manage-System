<template>
  <div class="dashboard-editor-container">
    <github-conner class="github-conner" />
    <panel-group @handleSetLineChartData="handleSetLineChartData" />
    <el-row style="background:#fff;padding:16px 16px 0;margin-bottom:32px;">
      <line-chart :chart-data="lineChartData" />
    </el-row>
    <el-row :gutter="32">
      <el-col :xs="24" :sm="24" :lg="8">
        <div class="chart-wrapper">
          <raddar-chart />
        </div>
      </el-col>
      <el-col> </el-col>
    </el-row>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
