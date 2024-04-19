<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
const appName = 'Test1'
</script>

<template>
  <div class="agreement">
    <div class="T_title" style="text-align: center">
      富兴数据智囊网站用户协议
    </div>
   
    <div class="T_title">
      一、注册与账户
    </div>
    <div class="T_content">
        用户需提供真实、准确的个人信息进行注册。
        用户应妥善保管账户信息，不得泄露给他人。
      <br><br>
    </div>

        <div class="T_title">
      二、使用规则
    </div>
    <div class="T_content">
        遵守法律法规，不得发布违法、有害、侵犯他人权益的内容。
        不得利用本网站进行商业活动或非法盈利。
      <br><br>
    </div>
        <div class="T_title">
      三、知识产权
    </div>
    <div class="T_content">
        本网站所包含的内容，包括但不限于文字、图像、音频、视频等，均受知识产权保护。
        用户不得复制、改编、传播本网站的内容。
      <br><br>
    </div>
        <div class="T_title">
      四、服务承诺
    </div>
    <div class="T_content">
        本网站将尽力提供稳定、可靠的服务。
        但不保证服务的连续性、准确性或完整性。
      <br><br>
    </div>
        <div class="T_title">
      五、免责声明
    </div>
    <div class="T_content">
        对于因使用本网站导致的任何损失或损害，本网站不承担责任。
        包括但不限于间接、特殊、附带或连带的损失。
      <br><br>
    </div>
        <div class="T_title">
     六、协议变更
    </div>
    <div class="T_content">
        本网站有权根据需要修改协议内容。变更后的协议将在网站上公布，用户继续使用本网站视为接受变更。
      <br><br>
    </div>
        <div class="T_title">
      七、法律适用与争议解决
    </div>
    <div class="T_content">
        本协议受[适用法律]管辖。如发生争议，双方应友好协商解决；协商不成的，可向有管辖权的法院提起诉讼。
    请仔细阅读并理解本用户协议。如有任何疑问，请联系我们。感谢您对富兴数据智囊网站的支持与配合。
      <br><br>
    </div>
  </div>
</template>

<style  scoped>
  .agreement {
    padding: 0px 25px;
    font-size: 14px;
    margin-bottom: 14px;
    color: #666666;

    background-color: #fff;
  }
  .T_title {
    font-size: 18px;
    font-weight: 600;
    margin: 1rem 0px;
    color: #666666;
  }
  .T_content {
    font-size: 14px;
    margin-bottom: 12px;
    /* color: #666; */
  }
  .title_content {
    font-size: 12px;
    margin-bottom: 12px;
    color: #666;
    margin-left: 12px;
    margin-right:12px;
  }
</style>
