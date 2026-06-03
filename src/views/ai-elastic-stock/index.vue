<template>
  <div class="ai-elastic-stock-page">
    <AnalysisView :embedded="true" />
  </div>
</template>

<script>
import AnalysisView from '@/views/ai-elastic-analysis'

export default {
  name: 'AIElasticStock',
  components: {
    AnalysisView
  }
}
</script>

<style lang="less" scoped>
.ai-elastic-stock-page {
  width: 100%;
}
</style>
