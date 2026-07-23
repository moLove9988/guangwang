<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Eilune Privacy Policy</h1>
      <p class="effective-date"><strong>Effective Date: July 23, 2026</strong></p>
      <p>This Privacy Policy explains the categories of information Eilune handles, where that information comes from, why it is used, when it may be shared, how long it is retained, and the choices available to you.</p>

      <h2>1. Scope</h2>
      <p>This Privacy Policy applies to Eilune and communications you have with us about Eilune. It should be read together with the Eilune User Agreement.</p>

      <h2>2. Information We Handle</h2>
      <p>We may handle account and profile information, including your email address, display name, profile details, and preferences; content and communications you choose to submit; interactions with content and other users; safety reports, blocks, and moderation records; digital-item balances; purchase product identifiers, transaction identifiers, and transaction status; and information you include when contacting support.</p>
      <p>When you choose to use camera or photo features, we handle only the media you capture, select, or save for the action you request. We do not receive your full payment-card information from Apple.</p>

      <h2>3. Sources of Information</h2>
      <p>We receive information directly from you, from your choices and activity in Eilune, from content or reports submitted by other users, from device features you authorize, and from Apple in connection with purchases.</p>

      <h2>4. How We Use Information</h2>
      <p>We use information to provide and maintain Eilune, manage accounts and preferences, present content according to user choices, complete requested transactions, respond to requests, protect users and rights, investigate reports, prevent fraud or misuse, enforce our terms, and comply with legal obligations.</p>
      <p>Information collected for one purpose will not be used for a materially different purpose without appropriate notice or consent unless permitted by law.</p>

      <h2>5. Permissions and User Choices</h2>
      <p>Device permissions are requested only when you choose an action that needs them. You may deny or withdraw camera or photo permission in iOS Settings, although the related action may then be unavailable. You decide what content to submit and may manage available profile, content, visibility, communication, and blocking choices within Eilune.</p>

      <h2>6. Content Visible to Others</h2>
      <p>Information and content you choose to make available to others may be seen, saved, or reshared by those recipients. Review your choices before sharing. Content not designated for sharing is not intended for public display.</p>

      <h2>7. Sharing and Disclosure</h2>
      <p>Information may be shared with other users according to your choices; with Apple for purchase processing; with your consent or at your direction; when required by law or valid legal process; or when reasonably necessary to protect users, rights, safety, and the integrity of Eilune.</p>
      <p>Any third party receiving personal information from us must protect it consistently with this Privacy Policy and applicable law. Apple handles information under its own terms and privacy policy.</p>

      <h2>8. Sale and Tracking</h2>
      <p>We do not sell personal information. We do not use personal information to track you across apps or websites owned by other companies for advertising.</p>

      <h2>9. Retention and Account Deletion</h2>
      <p>We retain information only for as long as reasonably necessary for the purposes described above, including maintaining safety, resolving disputes, enforcing agreements, and meeting legal obligations.</p>
      <p>You may initiate permanent account deletion from the account settings. Deletion removes the account and associated personal information and user content, except information that must be retained by law or is reasonably necessary for security, fraud prevention, or resolving reports and disputes. Records maintained independently by Apple are governed by Apple's policies.</p>

      <h2>10. Your Privacy Rights</h2>
      <p>You may update available account information, remove content, adjust sharing choices, withdraw device permissions, block users, and delete your account. Depending on applicable law, you may also request access, correction, deletion, a copy, restriction, or objection concerning your personal information.</p>
      <p>To submit a privacy request, contact <a href="mailto:support@eilune.com">support@eilune.com</a>. We may need to verify your request before acting on it.</p>

      <h2>11. Security</h2>
      <p>We use reasonable safeguards designed to protect information against unauthorized access, loss, disclosure, alteration, or misuse. No method of handling information can be guaranteed to be completely secure.</p>

      <h2>12. Changes to This Policy</h2>
      <p>We may update this Privacy Policy to reflect legal, safety, or service changes. The updated version applies from the effective date shown when it is made available.</p>

      <h2>13. Contact</h2>
      <p>For questions, privacy choices, or requests concerning personal information, contact <a href="mailto:support@eilune.com">support@eilune.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'EilunePrivacyPolicy'
}
</script>

<style scoped>
.agreement-page {
  box-sizing: border-box;
  width: 100%;
  min-height: 100vh;
  padding: 24px 18px;
  background: #ffffff;
  color: #222222;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  line-height: 1.7;
}

.agreement-section {
  max-width: 860px;
  margin: 0 auto;
}

h1 {
  margin: 0 0 16px;
  font-size: 28px;
  font-weight: 700;
  line-height: 1.3;
  color: #111111;
}

h2 {
  margin: 28px 0 10px;
  font-size: 18px;
  font-weight: 700;
  line-height: 1.4;
  color: #111111;
}

p {
  margin: 0 0 14px;
  font-size: 15px;
  color: #333333;
}

.effective-date {
  margin-bottom: 20px;
  color: #111111;
}

@media screen and (max-width: 600px) {
  .agreement-page {
    padding: 20px 16px;
  }

  h1 {
    font-size: 24px;
  }

  h2 {
    font-size: 17px;
  }

  p {
    font-size: 14px;
  }
}
</style>
