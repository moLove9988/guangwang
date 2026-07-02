<template>
  <div class="legal-page">
    <h1>Lanrei Privacy Agreement</h1>
    <p class="updated">Last updated: July 1, 2026</p>

    <p>This Privacy Agreement explains how Lanrei collects, uses, shares, stores, and protects information when you use our app. Lanrei is designed for festive social spaces, party rooms, video conversations, posts, and personalized greeting cards.</p>

    <h2>1. Information We Collect</h2>
    <p>Depending on how you use Lanrei, we may collect the following categories of information:</p>
    <ul>
      <li><strong>Account information:</strong> email address, nickname, password credentials, age, birthday, gender, profile photo, introduction, and account settings.</li>
      <li><strong>Profile and social information:</strong> followers, following, friend lists, blocked users, favorite rooms, favorite posts, likes, comments, reports, and user preferences.</li>
      <li><strong>Content you provide:</strong> photos, post captions, comments, room messages, greeting card text, generated card history, and other content you choose to create or share.</li>
      <li><strong>Photos and media:</strong> when you choose photos from your device, Lanrei uses those photos for the feature you selected, such as posting a moment, editing your profile, or creating a card.</li>
      <li><strong>Purchase information:</strong> virtual coin balance, purchase history, product identifiers, and transaction status provided by the app store.</li>
      <li><strong>Device and usage information:</strong> device type, app version, language, approximate region, interaction events, diagnostics, crash information, and security logs.</li>
    </ul>

    <h2>2. How We Use Information</h2>
    <p>Lanrei uses information to:</p>
    <ul>
      <li>Create and manage your account and profile.</li>
      <li>Provide party rooms, posts, comments, greeting cards, favorites, blocking, reporting, and other app features.</li>
      <li>Display content to other users according to your actions and privacy choices.</li>
      <li>Process virtual coin purchases and maintain your coin balance.</li>
      <li>Personalize the app experience and recommend rooms, posts, or users.</li>
      <li>Detect abuse, enforce community rules, prevent fraud, and protect user safety.</li>
      <li>Maintain, troubleshoot, analyze, and improve Lanrei.</li>
      <li>Comply with legal obligations and respond to lawful requests.</li>
    </ul>

    <h2>3. Sharing and Visibility</h2>
    <p>Some information is visible to other users, such as your nickname, profile photo, introduction, public posts, comments, and content you share in rooms or greeting cards. Users you interact with may see your activity based on the feature being used.</p>
    <p>We may share information with service providers who help us operate, host, analyze, secure, or support Lanrei. We may also share information when required by law, to protect rights and safety, to investigate abuse, or as part of a merger, acquisition, financing, or business transfer.</p>

    <h2>4. Photos, Camera, and Device Permissions</h2>
    <p>Lanrei requests access to photos or camera-related features only when needed for actions you choose, such as selecting images for a post, profile, or greeting card. You can manage permissions in your device settings. If permission is denied, related features may not work.</p>

    <h2>5. Video Calls and Party Rooms</h2>
    <p>Lanrei may process information required to support party rooms, room participation, messages, and video-related interactions. Room messages and participation details may be used for safety, moderation, support, and feature operation.</p>

    <h2>6. Virtual Coins and Payments</h2>
    <p>Payments are processed by the applicable app store. Lanrei receives purchase confirmation and related transaction information needed to deliver virtual coins and support purchase history. We do not receive your full payment card number from the app store.</p>

    <h2>7. Safety, Reports, and Blocked Users</h2>
    <p>When you report or block a user, Lanrei may store the related account identifiers, reason, details you provide, and associated content to review abuse, enforce rules, and prevent unwanted contact. Blocking may hide content from that user according to the app's safety features.</p>

    <h2>8. Data Retention</h2>
    <p>We keep information for as long as needed to provide Lanrei, maintain your account, comply with legal obligations, resolve disputes, enforce agreements, prevent abuse, and protect the app. Some information may be retained for a limited period after deletion where required for security, legal, or operational reasons.</p>

    <h2>9. Your Choices and Rights</h2>
    <p>You can update profile information in the app, manage blocked users, remove certain content, clear cache, and request account deletion where available. Depending on your location, you may have rights to access, correct, delete, or restrict use of certain personal information.</p>

    <h2>10. Account Deletion</h2>
    <p>If you delete your account, Lanrei will remove or de-identify account information according to applicable law and operational requirements. Some content already shared with others, safety records, transaction records, or legal records may remain where permitted or required.</p>

    <h2>11. Security</h2>
    <p>We use reasonable administrative, technical, and organizational safeguards designed to protect information. No method of transmission or storage is completely secure, so we cannot guarantee absolute security.</p>

    <h2>12. Adults Only</h2>
    <p>Lanrei is intended for users who are 18 or older. We do not knowingly allow minors to create accounts. If we learn that a minor has provided personal information, we may remove the account and related information.</p>

    <h2>13. International Use</h2>
    <p>Your information may be processed in countries or regions where Lanrei, its affiliates, or service providers operate. Data protection laws may differ from those in your location, but we take steps designed to protect information as described in this Privacy Agreement.</p>

    <h2>14. Changes to This Privacy Agreement</h2>
    <p>We may update this Privacy Agreement from time to time. If changes are material, we will provide notice in a reasonable way. Your continued use of Lanrei after the updated agreement takes effect means you acknowledge the updated terms.</p>

    <h2>15. Contact</h2>
    <p>If you have privacy questions or requests, contact us at <span class="contact">privacy@lanrei.app</span>.</p>
  </div>
</template>

<script setup>
defineOptions({
  name: 'LanreiPrivacyAgreement',
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
