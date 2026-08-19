<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({ name: 'IndexPage' })
</script>

<template>
  <!-- 滚动条遮罩容器，裁剪右侧滚动条 -->
  <div class="iframe-container">
    <iframe src="/my.html" class="content-iframe"></iframe>
  </div>
</template>

<style scoped>
.iframe-container {
  position: fixed;
  inset: 0;
  width: calc(100vw + 20px); /* 向右拓宽，把滚动条推出可视区域 */
  height: 100vh;
  overflow: hidden;
}

.content-iframe {
  width: 100%;
  height: 100%;
  border: none;
}
</style>