<template>
  <div class="chart-container">
    <chart height="100%" width="100%"/>
  </div>
</template>

<script>
import Chart from '@/components/Charts/keyboard'

export default {
  name: 'KeyboardChart',
  components: { Chart }
}
</script>

<style scoped>
.chart-container{
  position: relative;
  padding: 20px;
  width: 100%;
  height: 85vh;
}
</style>

