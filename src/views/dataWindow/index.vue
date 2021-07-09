<template>
  <div>
    
    数据集
    <LineData />
    <NowData /> 
  </div>
</template>

<script>
import LineData from '@/components/dataSet/LineData'
import NowData from '@/components/dataSet/nowData'

export default {
  components:{
    LineData,
    NowData,
  }
};
</script>

<style>

</style>
