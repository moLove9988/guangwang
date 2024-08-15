<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
const appName = 'ChatterEase'
export let privacyPolicy = `<p>&lt;h4&gt;A. Description of base income&lt;/h4&gt; &nbsp;<br>&lt;p&gt;1. The profit base ratio of the income is based on the pure profit excluding the 30% tax revenue from Apple and Google.&lt;/p &gt; &nbsp;<br>&lt;p&gt;2. We only have gifts that generate returns, with a base rate of 25%. The function to increase the base rate based on user quality will be implemented later.&lt;/p &gt;</p><p>&lt;h4&gt;B. VIP income explanation&lt;/h4&gt; &nbsp;<br>&lt;p&gt;1. VIP levels: Experience VIP, Regular VIP, Yearly VIP&lt;/p &gt; &nbsp;<br>&lt;p&gt;2. VIP experience only enjoys the rights of priority matching and unrestricted matching conditions, without any benefits.&lt;/p &gt;</p>`
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
