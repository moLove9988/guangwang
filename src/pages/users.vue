<template>
  <div class="legal-page">
    <h1>Lanrei User Agreement</h1>
    <p class="updated">Last updated: July 1, 2026</p>

    <p>Welcome to Lanrei. Lanrei is a social entertainment app for festive party rooms, video conversations, shared moments, and personalized greeting cards. This User Agreement explains the rules that apply when you access or use Lanrei.</p>
    <p>By creating an account, signing in, purchasing virtual items, posting content, joining rooms, sending messages, or otherwise using Lanrei, you agree to this User Agreement and our Privacy Agreement.</p>

    <h2>1. Eligibility</h2>
    <p>Lanrei is intended for adults. You must be at least 18 years old, or the age of majority in your jurisdiction if higher, to use Lanrei. You may not use the app if you are prohibited from doing so by applicable law.</p>

    <h2>2. Your Account</h2>
    <p>You are responsible for the information you provide and for activity that occurs through your account. Keep your sign-in information secure and do not allow others to use your account. You agree to provide accurate profile information and to update it when needed.</p>

    <h2>3. Lanrei Services</h2>
    <p>Lanrei may allow you to create or join virtual party rooms, communicate with other users, post holiday moments, follow users, save favorite rooms or posts, create greeting cards, purchase virtual coins, and use other interactive features. Features may change over time as we improve the app.</p>

    <h2>4. User Content</h2>
    <p>You keep ownership of photos, text, messages, greeting card content, profile information, and other content you submit to Lanrei. You grant Lanrei a limited, worldwide, non-exclusive license to host, store, display, process, adapt, and transmit your content as needed to operate, improve, protect, and promote the app.</p>
    <p>You confirm that you have the rights and permissions needed to upload or share your content, including permission from any people shown in photos or videos where required by law.</p>

    <h2>5. Community Rules</h2>
    <p>Lanrei is built for warm, respectful, adult social connection. You may not use Lanrei to:</p>
    <ul>
      <li>Harass, threaten, bully, exploit, impersonate, or target another person.</li>
      <li>Share sexual content involving minors or any content that exploits or harms children.</li>
      <li>Post unlawful, hateful, violent, deceptive, or severely harmful content.</li>
      <li>Share private information about another person without permission.</li>
      <li>Send spam, scams, malware, or misleading commercial messages.</li>
      <li>Use Lanrei to violate another person's intellectual property, privacy, or publicity rights.</li>
      <li>Attempt to disrupt, reverse engineer, scrape, overload, or misuse the app or its systems.</li>
    </ul>

    <h2>6. Moderation, Reports, and Blocking</h2>
    <p>Users can report content or accounts and block other users. Lanrei may review reported activity and may remove content, restrict features, suspend accounts, terminate accounts, or take other action when we believe it is necessary to protect users, comply with law, or enforce this Agreement.</p>

    <h2>7. Virtual Coins and Paid Features</h2>
    <p>Lanrei may offer virtual coins, paid greeting card generation, and other digital items. Virtual coins are licensed digital content, have no cash value, and cannot be exchanged for money unless required by law. Purchases are processed through the applicable app store. Refunds, billing support, and purchase disputes are handled under the app store's rules, except where applicable law provides otherwise.</p>

    <h2>8. Greeting Cards and Sharing</h2>
    <p>Greeting cards created through Lanrei are for personal communication and entertainment. You are responsible for the message, images, and recipients you choose. Do not use greeting cards to send illegal, abusive, misleading, or infringing content.</p>

    <h2>9. Privacy</h2>
    <p>Our Privacy Agreement describes how Lanrei collects, uses, stores, and shares information. By using Lanrei, you acknowledge that your information will be handled as described in the Privacy Agreement.</p>

    <h2>10. Account Termination</h2>
    <p>You may stop using Lanrei at any time and may request account deletion through the app where available. Lanrei may suspend or terminate access if you violate this Agreement, create risk for other users, or use the app in a way that may expose Lanrei or others to harm or liability.</p>

    <h2>11. Disclaimers</h2>
    <p>Lanrei is provided on an "as is" and "as available" basis. We do not guarantee that every feature will always be available, uninterrupted, secure, or error-free. User content and interactions are created by users, and Lanrei is not responsible for user conduct outside the scope required by applicable law.</p>

    <h2>12. Limitation of Liability</h2>
    <p>To the fullest extent permitted by law, Lanrei and its affiliates will not be liable for indirect, incidental, special, consequential, exemplary, or punitive damages, or for loss of profits, data, goodwill, or other intangible losses arising from your use of the app.</p>

    <h2>13. Changes to This Agreement</h2>
    <p>We may update this Agreement from time to time. If changes are material, we will provide notice in a reasonable way. Your continued use of Lanrei after changes become effective means you accept the updated Agreement.</p>

    <h2>14. Contact</h2>
    <p>If you have questions about this Agreement, contact us at <span class="contact">support@lanrei.app</span>.</p>
  </div>
</template>

<script setup>
defineOptions({
  name: 'LanreiUserAgreement',
});
</script>

<style scoped>
.legal-page {
  margin: 0;
  padding: 24px 20px 40px;
  font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
  line-height: 1.58;
  color: #262626;
  background: #fff;
  font-size: 15px;
  color-scheme: light;
}

h1 { margin: 0 0 8px; font-size: 28px; line-height: 1.12; color: #000; }

h2 { margin: 28px 0 8px; font-size: 19px; line-height: 1.25; color: #000; }

p { margin: 0 0 12px; }

ul { margin: 0 0 14px 20px; padding: 0; }

li { margin: 7px 0; }

.updated { color: #7a7a7a; margin-bottom: 22px; }

.contact { font-weight: 700; color: #9b3500; }
</style>
