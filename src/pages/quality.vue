<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
const appName = 'FateCamPro'
let contents = `<p>Diversification of ${appName}'s revenue &nbsp;<br>A. Description of base income<br>1. The profit base ratio of the income is based on the pure profit excluding the 30% tax revenue from Apple and Google.<br>2. We only have gifts that generate returns, with a base rate of 25%. The function to increase the base rate based on user quality will be implemented later.&nbsp;<br>&nbsp;<br>B. Video Revenue Explanation<br>1. The video duration is free, only gifts generate revenue. &nbsp;<br>2. The income base in the video is 25%. For example, if you receive gifts worth 10,000 gold coins in a video, you will get 10,000 * 0.7 * 0.25 = 1,750 gold coins.<br>3. The income base in the video is 25%, and VIP increases the income base by 5%. For example, if you receive gifts worth 10,000 gold coins in a video, you will receive 10,000 * 0.7 * 0.30 = 2,100 gold coins.</p>`
</script>

<template>
  <div class="protocol" v-html="contents">

  </div>
</template>

<style scoped>
  .protocol {
    font-size: 14px;
    margin-bottom: 14px;
    color: #000;
    margin-left:6px;
    margin-right:6px;
    background-color: fff;
    
  }
  .bt {
    font-size: 20px;
    margin: 6px 0px;
    color: #7f1146;
  }
</style>
