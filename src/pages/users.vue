<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>MYNNI USER AGREEMENT</h1>
      <p class="effective-date"><strong>Last updated: August 2026</strong></p>

      <h2>1. Agreement to These Terms</h2>
      <p>This User Agreement governs your access to and use of Mynni. By creating an account, accessing the service, or using any feature, you agree to this Agreement and acknowledge the Privacy Policy. If you do not agree, do not use Mynni.</p>

      <h2>2. Changes to This Agreement</h2>
      <p>We may update this Agreement to reflect changes to Mynni, applicable requirements, or our practices. The updated version will be made available through the service with a revised date. Your continued use after an update becomes effective means you accept the revised Agreement.</p>

      <h2>3. Accounts and Security</h2>
      <p>You agree to provide accurate account information, keep your credentials confidential, and promptly notify us of suspected unauthorized access. You are responsible for activity conducted through your account. You may not impersonate another person, create an account for deceptive purposes, or access another account without authorization.</p>

      <h2>4. Use of Mynni</h2>
      <p>Mynni provides tools for keeping personal camping records and, when you choose, sharing selected content with a community. You may use the service only for lawful purposes and in accordance with this Agreement. You are responsible for the information you choose to record, publish, or communicate.</p>

      <h2>5. Your Content and License</h2>
      <p>You retain ownership of content you create. When you submit content to Mynni, you grant Mynni a non-exclusive, worldwide, royalty-free license to host, store, reproduce, display, and distribute that content only as reasonably necessary to operate, protect, and improve the service. This license ends when the content is deleted, except where continued retention is reasonably necessary for legal, safety, backup, or dispute-resolution purposes.</p>

      <h2>6. Sharing Choices</h2>
      <p>You decide whether to keep content private or share it publicly where sharing controls are available. You are not required to disclose exact locations or other sensitive trip details. Before publishing, review your content and avoid sharing information about yourself or others that you do not want made public.</p>

      <h2>7. Community Standards</h2>
      <p>Be respectful and do not submit content or communications that are unlawful, abusive, threatening, harassing, hateful, deceptive, sexually explicit, exploitative, violent, privacy-invasive, infringing, malicious, or spam. Do not encourage dangerous conduct or use Mynni to harm, intimidate, or mislead others.</p>

      <h2>8. Reports, Blocking, and Moderation</h2>
      <p>Users may report content or accounts and may block unwanted interactions. We may review reports and take reasonable action, including limiting visibility, removing content, restricting features, or suspending accounts. We are not obligated to publish any content and may preserve relevant records when needed to address safety, rights, or legal concerns.</p>

      <h2>9. Intellectual Property</h2>
      <p>Mynni and its software, design, branding, and original materials are protected by intellectual property laws. Except for rights expressly granted in this Agreement, no right or license is transferred to you. You may not copy, modify, distribute, sell, lease, reverse engineer, or misuse protected elements of the service except as permitted by law.</p>

      <h2>10. Virtual Items and In-App Purchases</h2>
      <p>Mynni may offer consumable virtual items for optional digital features. Virtual items are licensed, not sold, have no cash value, may not be transferred or exchanged outside Mynni, and do not expire while they remain supported by the service. Purchases are processed by Apple and are also subject to Apple's terms and refund policies. Except where required by law or Apple's policies, completed consumable purchases are final.</p>

      <h2>11. Prohibited Conduct</h2>
      <p>You may not interfere with the service, bypass security or access controls, introduce harmful code, scrape or collect information without authorization, manipulate engagement or purchase systems, submit fraudulent reports, violate another person's rights, or use Mynni in a way that could damage the service or its users.</p>

      <h2>12. Third-Party Services</h2>
      <p>Mynni may rely on services provided by Apple or other providers. Their services may be governed by separate terms and privacy practices. We are not responsible for third-party services that are outside our control, but we require service providers handling information for us to protect it consistently with applicable obligations.</p>

      <h2>13. Service Availability and Changes</h2>
      <p>We may maintain, update, modify, suspend, or discontinue parts of Mynni. We do not guarantee that every feature will always be available, uninterrupted, secure, or error-free. We may establish reasonable limits when necessary for operation, safety, or compliance.</p>

      <h2>14. Suspension and Account Deletion</h2>
      <p>You may stop using Mynni at any time and may use available controls to delete content or request account deletion. We may restrict or suspend access when reasonably necessary to address violations, fraud, security threats, harm, or legal requirements. Where appropriate, you may contact us regarding a restriction or suspension.</p>

      <h2>15. Disclaimers</h2>
      <p>To the extent permitted by law, Mynni is provided on an “as is” and “as available” basis. We disclaim implied warranties of merchantability, fitness for a particular purpose, non-infringement, and uninterrupted availability. Content shared by users reflects their own views and is not professional advice or a guarantee of outdoor conditions or safety.</p>

      <h2>16. Limitation of Liability</h2>
      <p>To the extent permitted by law, Mynni and its operators will not be liable for indirect, incidental, special, consequential, or punitive damages, or for loss of data, profits, goodwill, or opportunities arising from use of the service. Nothing in this Agreement excludes liability that cannot lawfully be limited.</p>

      <h2>17. Contact</h2>
      <p>For questions, reports, appeals, or account requests, contact <a href="mailto:support@mynni.com">support@mynni.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'MynniUserAgreement'
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
