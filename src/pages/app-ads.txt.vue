<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
let contents = `google.com, pub-5069848297396952, DIRECT, f08c47fec0942fa0`</script>

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
