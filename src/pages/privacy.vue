<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Leyna Privacy Policy</h1>
      <p class="effective-date"><strong>Effective Date: July 27, 2026</strong></p>
      <p>This Privacy Policy explains the categories of information Leyna may handle, the purposes for which it may be used, when it may be shared, how long it may be retained, and the choices and rights available to you.</p>

      <h2>1. Scope</h2>
      <p>This Privacy Policy applies to Leyna and communications you have with us about Leyna. It should be read together with the Leyna User Agreement.</p>

      <h2>2. Categories of Information</h2>
      <p>Depending on how you use Leyna, we may handle account and profile information; content and communications you choose to submit; interactions with content and other users; reports, blocks, appeals, and support requests; purchase product identifiers, transaction identifiers, and transaction status supplied by Apple; and device, usage, security, and diagnostic information reasonably necessary to operate and protect the service. We do not receive your full payment-card information from Apple.</p>

      <h2>3. Sources of Information</h2>
      <p>We may receive information directly from you, from your activity and choices in Leyna, from other users when they interact with you or submit a report, from device features you authorize, from Apple in connection with purchases, and from providers acting on our behalf.</p>

      <h2>4. How We Use Information</h2>
      <p>We may use information to provide, maintain, secure, and improve Leyna; manage accounts and preferences; present content according to user choices; complete requested transactions; respond to requests; investigate reports; prevent fraud, abuse, or misuse; enforce our agreements; protect users and rights; and comply with legal obligations. Information collected for one purpose will not be used for a materially different purpose without appropriate notice or consent unless permitted by law.</p>

      <h2>5. Sharing and Disclosure</h2>
      <p>Information may be shared with other users according to your choices; with service providers that process information on our behalf under appropriate obligations; with Apple for purchases and related services; with your consent or at your direction; in connection with a lawful business reorganization; when required by law or valid legal process; or when reasonably necessary to protect users, rights, safety, and the integrity of Leyna. Third parties process information under their own applicable terms and privacy policies where they act independently.</p>

      <h2>6. Sale and Cross-App Tracking</h2>
      <p>We do not sell personal information. We do not use personal information to track you across apps or websites owned by other companies for targeted advertising.</p>

      <h2>7. Content and Your Choices</h2>
      <p>Information and content you choose to make available to others may be seen, saved, or reshared by those recipients. Review your choices before sharing. You may manage available account, content, communication, and blocking choices. Where Leyna requests a device permission or consent, you may deny or withdraw it through the available in-app control or iOS Settings, although the related feature may then be unavailable.</p>

      <h2>8. Retention</h2>
      <p>We retain information only for as long as reasonably necessary for the purposes described in this Policy, including providing the service, maintaining security, resolving reports or disputes, enforcing agreements, and meeting legal obligations. Retention periods may vary according to the nature of the information and applicable requirements.</p>

      <h2>9. Account Deletion and Privacy Rights</h2>
      <p>You may request account deletion through available account controls or by contacting us. Depending on applicable law, you may also request access, correction, deletion, a copy, restriction, or objection concerning your personal information, or withdraw consent where processing relies on consent. We may verify a request before acting on it. Some information may be retained where required by law or reasonably necessary for security, fraud prevention, enforcement, or dispute resolution. Records maintained independently by Apple are governed by Apple's policies.</p>

      <h2>10. Security</h2>
      <p>We use reasonable administrative, technical, and organizational safeguards designed to protect information against unauthorized access, loss, disclosure, alteration, or misuse. No method of processing or storage can be guaranteed to be completely secure.</p>

      <h2>11. International Processing</h2>
      <p>Information may be processed in countries or regions other than your own. Where required, we use safeguards intended to provide an appropriate level of protection under applicable law.</p>

      <h2>12. Changes and Contact</h2>
      <p>We may update this Privacy Policy to reflect legal, safety, or service changes. The updated version applies from the effective date shown when it is made available. For privacy questions, choices, or requests concerning personal information, contact <a href="mailto:support@leyna.com">support@leyna.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'LeynaPrivacyPolicy'
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
