<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Antje Privacy Policy</h1>
      <p class="effective-date"><strong>Effective Date: July 21, 2026</strong></p>
      <p>Antje (the “Service,” “we,” “us,” or “our”) respects your privacy. This Privacy Policy explains what information we collect and process, how we use and share it, how long we retain it, and the choices available to you.</p>

      <h2>1. Scope</h2>
      <p>This Privacy Policy applies to information processed in connection with Antje and to communications you send to us about the Service. Third-party services may provide separate privacy notices for information they process independently.</p>

      <h2>2. Information We Collect and Process</h2>
      <p><strong>Account and profile information.</strong> This includes your email address, display name, profile details, images, and preferences that you choose to provide.</p>
      <p><strong>Content and communications.</strong> This includes content that you choose to create, publish, send, or submit, together with related interactions and safety actions.</p>
      <p><strong>Media.</strong> This includes photos, videos, camera input, microphone input, or other media that you choose to provide after granting any required device permission.</p>
      <p><strong>Purchase information.</strong> This includes product, transaction, and purchase-status records. Payment credentials are processed by the applicable payment provider and are not received by us in full.</p>
      <p><strong>Support information.</strong> This includes your contact details, message, and any related information that you choose to provide.</p>

      <h2>3. How We Collect Information</h2>
      <p>We collect information directly from you when you create or update an account, provide content, communicate with others, make a purchase, request support, or otherwise choose to submit information. We also create limited records of actions necessary to provide the Service, maintain safety, and fulfill your requests.</p>

      <h2>4. How We Use Information</h2>
      <p>We use information to provide and personalize the Service, maintain accounts and preferences, deliver content and communications, fulfill purchases, respond to requests, enforce community standards, investigate reports, prevent fraud and misuse, protect rights and safety, and comply with legal obligations. We do not use information for a materially different purpose without an appropriate legal basis or additional permission when required.</p>

      <h2>5. Device Permissions and Your Choices</h2>
      <p>Device access is requested only when you choose an action that requires it. You can deny or withdraw permission in iOS Settings. You may also choose not to provide optional information, although some requested features may then be unavailable.</p>

      <h2>6. Public Information and Other Users</h2>
      <p>Information you choose to publish may be visible to other users. Information you send to a recipient is available to that recipient, who may retain it after you delete your copy. Review content before sharing it and do not disclose another person’s information without permission.</p>

      <h2>7. Service Providers and Other Disclosures</h2>
      <p>We may share information with service providers that process it on our behalf to provide requested services, process purchases, support operations, maintain security, or comply with law. They are required to provide protection consistent with this Policy and may use information only for the authorized purpose.</p>
      <p>We may also disclose information when you direct us to do so, when required by law, or when reasonably necessary to protect rights, safety, and security. We do not sell personal information or permit service providers to use it for their own advertising.</p>

      <h2>8. Retention and Deletion</h2>
      <p>We retain information only for as long as reasonably necessary for the purposes described in this Policy, including providing the Service, maintaining security, resolving disputes, preventing abuse, and meeting legal obligations.</p>
      <p>You may delete your account using the account controls or contact us to request deletion. Some information may remain where retention is required by law, necessary for security or fraud prevention, retained by another user, or maintained independently by a third party.</p>

      <h2>9. Security</h2>
      <p>We use reasonable safeguards designed to protect information against unauthorized access, loss, disclosure, alteration, or misuse. No method of storage or transmission can be guaranteed completely secure.</p>

      <h2>10. Your Rights and Choices</h2>
      <p>Depending on applicable law, you may request access to, correction of, deletion of, or restriction of your personal information. You may withdraw consent for future processing where consent applies. Withdrawing consent does not affect processing already completed. We may request reasonable information to verify your request.</p>

      <h2>11. Changes to This Policy</h2>
      <p>We may update this Privacy Policy to reflect changes in law or the Service. If a change is material, we will provide notice through the Service or another appropriate method.</p>

      <h2>12. Contact Us</h2>
      <p>For privacy questions, rights requests, or account deletion assistance, contact <a href="mailto:support@antje.com">support@antje.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'AntjePrivacyPolicy'
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
