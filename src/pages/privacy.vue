<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Saya Privacy Policy</h1>
      <p class="effective-date"><strong>Effective Date: July 21, 2026</strong></p>
      <p>This Privacy Policy explains what information Saya handles, how it is obtained and used, when it may be shared, how long it is retained, and the choices available to you.</p>
      <p>Please review this Privacy Policy before using Saya.</p>

      <h2>1. Scope and Sources</h2>
      <p>This Privacy Policy applies to Saya and support communications relating to Saya.</p>
      <p>Information is obtained directly from you when you enter account or profile details, create or submit content, interact with the service, make a purchase, change preferences, or contact support.</p>

      <h2>2. Information We Handle</h2>
      <p>Saya may handle account and profile information, such as an email address, display name, and profile details; content you create or submit; service activity, interactions, safety reports, preferences, and virtual-item balances; purchase item and transaction status; and information included in support communications.</p>
      <p>Saya does not receive your full payment-card details from Apple.</p>

      <h2>3. Camera and Photo Access</h2>
      <p>Camera or photo access is requested only when you choose a feature that requires capturing, selecting, or saving an image. Saya handles only the images you choose or create for that purpose.</p>
      <p>You can deny or withdraw device permissions in iOS Settings.</p>

      <h2>4. How We Use Information</h2>
      <p>Information is used to provide and maintain Saya, manage accounts and user choices, present and organize content, complete requested purchases, support safety features, respond to support requests, prevent misuse, and comply with legal obligations.</p>

      <h2>5. Public Content</h2>
      <p>Profile information, content, comments, and activity you choose to make public may be displayed in public areas of Saya. Content you keep private is not intended for public display. Review content carefully before making it public.</p>

      <h2>6. Sharing and Third Parties</h2>
      <p>Apple processes in-app purchases under Apple's terms and privacy policy. Information may also be disclosed with your consent, when required by law, or when reasonably necessary to protect users, rights, safety, or the service.</p>
      <p>Any third party that receives personal information must provide protection consistent with this Privacy Policy and applicable law.</p>

      <h2>7. Sale and Tracking</h2>
      <p>Saya does not sell personal information and does not use personal information to track you across apps or websites owned by other companies for advertising.</p>

      <h2>8. Retention and Deletion</h2>
      <p>Information is retained only for as long as reasonably necessary for the purposes described in this Privacy Policy or as required by law.</p>
      <p>You may initiate deletion of your account and associated information from the account settings or request assistance at <a href="mailto:support@saya.com">support@saya.com</a>. Records maintained independently by Apple are governed by Apple's policies.</p>

      <h2>9. Your Choices and Rights</h2>
      <p>You can update available account information, manage content visibility, remove content, change device permissions, and delete your account. These controls allow you to withdraw consent for the corresponding use of information.</p>
      <p>Depending on applicable law, you may request access, correction, deletion, a copy, restriction, or objection concerning personal information by contacting <a href="mailto:support@saya.com">support@saya.com</a>.</p>

      <h2>10. Security</h2>
      <p>Reasonable safeguards are used to protect information against unauthorized access, loss, disclosure, alteration, or misuse. No method of handling information can be guaranteed to be completely secure.</p>

      <h2>11. Children and Changes</h2>
      <p>Saya is not intended for children who are not legally permitted to use the service. If information from a child is handled in violation of applicable law, appropriate steps will be taken to delete it.</p>
      <p>We may update this Privacy Policy to reflect changes in law or the service. The updated version applies from the effective date shown when it is made available.</p>

      <h2>12. Contact</h2>
      <p>For questions about this Privacy Policy, privacy choices, or requests concerning personal information, contact <a href="mailto:support@saya.com">support@saya.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'SayaPrivacyPolicy'
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
