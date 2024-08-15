<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
const appName = 'ChatterEase'
export let privacyPolicy = `<p><strong>Welcome to ${appName}</strong></p><p><strong>1. Acceptance of Terms</strong></p><p>This End User License Agreement (the "Agreement") is a legal agreement between you (either an individual or a single entity) and the developers of the ${appName} software product ("${appName}"). By installing, copying, or otherwise using ${appName}, you agree to be bound by the terms and conditions of this Agreement. If you do not agree to the terms of this Agreement, do not install or use ${appName}.</p><p><strong>2. Grant of License</strong></p><p>${appName}'s developers grant you a non-exclusive, non-transferable, worldwide license to use ${appName} in your personal or commercial projects. You may:</p><p>Install and use ${appName} in a single project.</p><p>Make backup copies of ${appName} for archival purposes only.</p><p><strong>3. Restrictions</strong></p><p>You may not:</p><p>Copy the source code or user interface design of ${appName}, except for backup or archival purposes.</p><p>Modify, decompile, disassemble, or create derivative works of ${appName}.</p><p>Rent, lease, sell, or distribute copies of ${appName} without prior written consent from ${appName}'s developers.</p><p>Remove any copyright notices or other proprietary notices from ${appName} or any part thereof.</p><p><strong>4. Intellectual Property</strong></p><p>${appName} and all copies thereof, including but not limited to related documentation, images, icons, animations, video, music, text, and accompanying software, are the property of ${appName}'s developers or their suppliers and are protected by international copyright laws and other intellectual property laws.</p><p><strong>5. Disclaimer of Warranty</strong></p><p>${appName}'s developers do not warrant that ${appName} will operate error-free or that it is suitable for any particular purpose.</p>`
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
