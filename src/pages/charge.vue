<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
const appName = 'ChatterEase'
export let privacyPolicy = `<p>**Recharge Agreement for ${appName}**</p><p>**Welcome to ${appName} Recharge Services**</p><p>**1. Acceptance of Terms**</p><p>This Recharge Agreement (the "Agreement") is a legal agreement between you (either an individual or a single entity) and the service providers of ${appName} ("${appName} Service Providers"). By accessing or using the recharge services provided by ${appName}, you agree to be bound by the terms and conditions of this Agreement. If you do not agree to the terms of this Agreement, do not use the recharge services.</p><p>**2. Description of Service**</p><p>${appName} Service Providers offer recharge services that allow you to purchase additional features, functionalities, or credits for your use of ${appName}. The specific services available for recharge will be detailed on the ${appName} recharge page or within the ${appName} application.</p><p>**3. Recharge Procedures**</p><p>To recharge your ${appName} account, you must:</p><p>- Select the desired recharge package or feature.<br>- Complete the payment process using the accepted payment methods as provided.<br>- Confirm the transaction and agree to the terms of the recharge.</p><p>**4. Payment**</p><p>All payments for recharges must be made in the currency specified by ${appName} Service Providers and through the accepted payment methods. By making a payment, you authorize ${appName} Service Providers to charge your chosen payment method for the amount of the recharge package.</p><p>**5. Refund Policy**</p><p>Recharges are generally non-refundable. However, in cases where a refund is applicable, such as in the event of a service failure or error, you may request a refund by contacting ${appName} customer support within the specified time frame and in accordance with the refund policy outlined by ${appName} Service Providers.</p><p>**6. Use of Recharge Credits**</p><p>Recharge credits or features are for your personal or commercial use within ${appName} and cannot be transferred to other users or redeemed for cash. The expiration and usage of recharge credits will be governed by the terms specified at the time of recharge.</p><p>**7. Modifications to Recharge Services**</p><p>${appName} Service Providers reserve the right to modify, suspend, or discontinue the recharge services at any time without notice. ${appName} Service Providers will not be liable to you or any third party for any modification, suspension, or discontinuance of the recharge services.</p><p>**8. Termination**</p><p>Either party may terminate this Agreement at any time by ceasing to use the recharge services. Upon termination, any unused recharge credits may be forfeited.</p><p>**9. Disclaimer of Warranty**</p><p>The recharge services are provided on an "as is" and "as available" basis. ${appName} Service Providers do not warrant that the recharge services will be uninterrupted, timely, secure, or error-free.</p><p>**10. Limitation of Liability**</p><p>${appName} Service Providers will not be liable for any indirect, incidental, special, consequential, or punitive damages, or any loss of profits or revenues, whether incurred directly or indirectly, or any loss of data, use, goodwill, or other intangible losses, resulting from (a) your access to or use of or inability to access or use the recharge services; (b) any conduct or content of any third party on the recharge services, including without limitation, any defamatory, offensive, or illegal conduct of other users or third parties; (c) any content obtained from the recharge services; or (d) unauthorized access, use, or alteration of your transmissions or content.</p><p>**11. Governing Law**</p><p>This Agreement shall be governed by and construed in accordance with the laws of the jurisdiction in which ${appName} Service Providers operate, without regard to its conflict of law principles.</p><p>**12. Entire Agreement**</p><p>This Agreement constitutes the entire agreement between you and ${appName} Service Providers regarding the use of the recharge services and supersedes all prior agreements and understandings, whether written or oral, relating to such subject matter.</p><p>By proceeding with a recharge, you acknowledge that you have read, understood, and agree to be bound by this Recharge Agreement.</p>`
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
