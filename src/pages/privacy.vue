<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>MYNNI PRIVACY POLICY</h1>
      <p class="effective-date"><strong>Last updated: August 2026</strong></p>

      <h2>1. Scope</h2>
      <p>This Privacy Policy explains how Mynni handles information when you access or use the service. It applies to information processed through Mynni and does not replace the privacy terms of Apple or other services that operate independently.</p>

      <h2>2. Information You Provide</h2>
      <p>We may process information you submit, including account details, profile information, communications with support, and information included in requests or reports. You are responsible for ensuring that information you provide about another person is shared lawfully.</p>

      <h2>3. Content and Community Activity</h2>
      <p>We may process content you create or share, related metadata you choose to include, and community activity such as reactions, messages, reports, and blocks. Content kept private is not made public by Mynni. Content you choose to publish may be visible to other users.</p>

      <h2>4. Purchase Information</h2>
      <p>When you make an in-app purchase, Apple processes the payment. Mynni may receive limited purchase information, such as the product and transaction identifiers and purchase status, to provide the purchased item, maintain transaction integrity, and prevent duplicate fulfillment. Mynni does not receive your full payment-card details.</p>

      <h2>5. Technical and Usage Information</h2>
      <p>We may process limited device, usage, diagnostic, and security information generated when Mynni is used. This may include app version, operating-system information, interactions with the service, crash information, and records needed to maintain reliability, protect accounts, and investigate misuse.</p>

      <h2>6. How We Use Information</h2>
      <p>We use information to provide and maintain Mynni, authenticate accounts, preserve user settings, display content according to sharing choices, support community interactions, fulfill purchases, respond to requests, enforce our User Agreement, prevent abuse, protect users and rights, improve reliability, and comply with applicable obligations.</p>

      <h2>7. Public and Shared Content</h2>
      <p>You control which eligible content and details you choose to make public. You do not need to disclose exact locations or other sensitive information. Public content may be viewed, copied, or shared by others, so review it carefully before publishing. Removing content from Mynni may not remove copies previously saved by other users.</p>

      <h2>8. Service Providers</h2>
      <p>We may use service providers to support hosting, storage, security, diagnostics, moderation, customer support, and other service operations. They may process information only for authorized purposes and must provide protections consistent with this Policy and applicable requirements.</p>

      <h2>9. Legal and Safety Disclosures</h2>
      <p>We may preserve or disclose information when reasonably necessary to comply with law or valid legal process, protect the rights and safety of users or others, investigate fraud or security incidents, enforce our agreements, or respond to an emergency. We may also disclose information as part of a business transfer subject to appropriate safeguards.</p>

      <h2>10. Data Sales, Advertising, and Tracking</h2>
      <p>We do not sell personal information. We do not use information collected through Mynni to track you across apps or websites owned by other companies for targeted advertising. If these practices change, we will provide appropriate notice and obtain consent where required.</p>

      <h2>11. Data Retention</h2>
      <p>We retain information only for as long as reasonably necessary for the purposes described in this Policy. Retention periods may vary based on the nature of the information, account status, user requests, backups, security needs, unresolved reports or disputes, and applicable legal obligations. Information may be deleted or de-identified when it is no longer needed.</p>

      <h2>12. Security</h2>
      <p>We use reasonable administrative, technical, and organizational safeguards designed to protect information. No method of storage or transmission is completely secure, and we cannot guarantee absolute security. You should protect your credentials and contact us if you suspect unauthorized account activity.</p>

      <h2>13. Your Controls and Permissions</h2>
      <p>Some optional features may request access to device capabilities or information. The operating system presents these requests, and access occurs only after permission is granted. You can deny or revoke permissions in device settings, although the related optional features may then be unavailable. Where supported, you can choose what to submit manually.</p>

      <h2>14. Access, Correction, and Deletion</h2>
      <p>You may use available controls to update profile information, manage sharing, delete content, report or block users, and request account deletion. Depending on applicable law, you may also request access to, correction of, deletion of, restriction of, or a copy of personal information associated with you. We may need to verify a request before completing it.</p>

      <h2>15. Changes to This Policy</h2>
      <p>We may update this Privacy Policy to reflect changes to Mynni, applicable requirements, or our practices. The revised Policy will be made available through the service with an updated date. We will provide additional notice or request consent when required.</p>

      <h2>16. Contact</h2>
      <p>For privacy questions or requests concerning personal information, contact <a href="mailto:support@mynni.com">support@mynni.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'MynniPrivacyPolicy'
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
