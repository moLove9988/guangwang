<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Mycko Privacy Policy</h1>
      <p class="effective-date"><strong>Effective Date: July 28, 2026</strong></p>
      <p>This Privacy Policy explains how Mycko collects, uses, discloses, retains, and protects information when you use the app or communicate with us.</p>

      <h2>1. Scope</h2>
      <p>This Privacy Policy applies to Mycko and related communications. It should be read together with the Mycko User Agreement.</p>

      <h2>2. Information We Collect</h2>
      <p>Depending on how you use Mycko, we may collect account and contact information; profile information; content, media, and communications you choose to provide; activity, preferences, and interactions; purchase and transaction records; support, safety, and moderation information; and device, log, and diagnostic information.</p>
      <p>Payment information is processed by Apple. We do not receive your full payment-card details.</p>

      <h2>3. Sources of Information</h2>
      <p>We receive information directly from you, automatically through your use of Mycko, from device features you authorize, from Apple and service providers, and from other people when they interact with you or submit content or reports involving you.</p>

      <h2>4. How We Use Information</h2>
      <p>We use information to provide, maintain, personalize, and improve Mycko; manage accounts and preferences; process requested transactions; enable communications and sharing choices; respond to support requests; protect users, rights, and the service; prevent fraud, abuse, and security incidents; enforce our terms; and comply with legal obligations.</p>
      <p>We will not use information for a materially different purpose without appropriate notice or consent unless permitted by law.</p>

      <h2>5. Permissions and User Choices</h2>
      <p>Mycko may request access to device features only when relevant to an action you choose. You can deny or withdraw permissions in iOS Settings, although related features may then be unavailable. You can also manage available account, profile, content, visibility, communication, and safety choices within Mycko.</p>

      <h2>6. Content Visible to Others</h2>
      <p>Information and content you choose to make available to others may be viewed, saved, or reshared by recipients. Review your choices before sharing and avoid submitting information you do not want others to receive.</p>

      <h2>7. Sharing and Disclosure</h2>
      <p>We may disclose information to other users according to your choices; to vendors and service providers acting on our behalf; to Apple in connection with app distribution and purchases; with your consent or at your direction; in connection with a business transfer; when required by law or valid legal process; or when reasonably necessary to protect users, rights, safety, and Mycko.</p>
      <p>We require service providers and other third parties that process personal information on our behalf to provide the same or equivalent protection described in this Privacy Policy and required by applicable law. Third parties, including Apple, may also handle information independently under their own terms and privacy policies.</p>

      <h2>8. Sale and Tracking</h2>
      <p>We do not sell personal information. We do not use personal information to track you across apps or websites owned by other companies for advertising.</p>

      <h2>9. Retention</h2>
      <p>We retain information only for as long as reasonably necessary for the purposes described in this Privacy Policy, including providing the service, maintaining security and safety, completing transactions, resolving disputes, enforcing agreements, and meeting legal obligations. Retention periods may vary based on the nature of the information and applicable requirements.</p>

      <h2>10. Your Choices and Privacy Rights</h2>
      <p>You may update available account information, manage or remove content, adjust sharing choices, withdraw device permissions, use available safety controls, and initiate account deletion. Depending on applicable law, you may also request access, correction, deletion, a copy, restriction, or objection concerning your personal information.</p>
      <p>To submit a privacy request, contact <a href="mailto:support@mycko.com">support@mycko.com</a>. We may need to verify your identity and request before acting. Some information may be retained where permitted or required by law.</p>

      <h2>11. Security</h2>
      <p>We use reasonable safeguards designed to protect information against unauthorized access, loss, disclosure, alteration, or misuse. No method of handling information can be guaranteed to be completely secure.</p>

      <h2>12. International Processing</h2>
      <p>Information may be processed in countries other than the one where you live. Where required, we use appropriate safeguards for cross-border transfers.</p>

      <h2>13. Changes to This Policy</h2>
      <p>We may update this Privacy Policy to reflect legal, safety, or service changes. The updated version applies from the effective date shown when it is made available.</p>

      <h2>14. Contact</h2>
      <p>For questions, privacy choices, or requests concerning personal information, contact <a href="mailto:support@mycko.com">support@mycko.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'MyckoPrivacyPolicy'
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
