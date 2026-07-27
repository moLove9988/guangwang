<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Leyna User Agreement</h1>
      <p class="effective-date"><strong>Effective Date: July 27, 2026</strong></p>
      <p>This User Agreement governs your access to and use of Leyna. By accessing or using Leyna, you agree to this Agreement and the Privacy Policy. If you do not agree, do not use Leyna.</p>

      <h2>1. Use of Leyna</h2>
      <p>You may use Leyna only in compliance with this Agreement and applicable law. You may not use Leyna in a way that interferes with the rights of others, the integrity of the service, or the lawful operation of any network or system.</p>

      <h2>2. Accounts</h2>
      <p>You agree to provide accurate information, keep your credentials secure, and promptly update information that changes. You are responsible for activity associated with your account. You may not impersonate another person, create an account through deceptive means, transfer an account without permission, or access another person's account without authorization.</p>

      <h2>3. User Content</h2>
      <p>You retain ownership of content you submit and are responsible for ensuring that you have all rights and permissions needed to submit it. You grant Leyna a worldwide, non-exclusive, royalty-free license to host, reproduce, format, display, and distribute that content only as reasonably necessary to provide the service, respect your sharing choices, protect users and rights, and comply with law. This license ends when the content is deleted, except where limited retention is legally permitted or reasonably necessary to resolve a report or dispute.</p>

      <h2>4. Acceptable Use</h2>
      <p>You must not submit, request, encourage, or distribute content or conduct that is unlawful, fraudulent, threatening, harassing, hateful, discriminatory, sexually explicit, exploitative, violent, deceptive, invasive of privacy, or otherwise harmful. You must not infringe intellectual-property or other rights, disclose another person's private information without permission, spam, manipulate engagement, distribute malicious material, evade restrictions, interfere with the service, or misuse safety controls.</p>

      <h2>5. Community Safety and Enforcement</h2>
      <p>You may use available reporting and blocking controls or contact us about content or conduct that may violate this Agreement. We may review reports, remove or restrict content, limit interactions, suspend or terminate access, preserve relevant information, or take other appropriate action to enforce this Agreement, protect users or rights, address safety concerns, or comply with law.</p>

      <h2>6. Leyna Materials</h2>
      <p>Leyna and its names, logos, designs, text, graphics, software, and other materials are protected by intellectual-property laws. Subject to this Agreement, you receive a limited, personal, revocable, non-exclusive, and non-transferable right to use Leyna for lawful purposes. No other rights are granted.</p>

      <h2>7. Purchases and Digital Items</h2>
      <p>Optional purchases are processed by Apple and are also subject to Apple's applicable terms and the terms presented at purchase. Digital items are licensed, not sold, have no cash value, and may not be sold or transferred outside Leyna. Payments and refund decisions are handled under Apple's rules and applicable law.</p>

      <h2>8. Suspension, Termination, and Account Deletion</h2>
      <p>You may stop using Leyna or request account deletion through available account controls or by contacting us. We may suspend or terminate access when reasonably necessary because of a violation of this Agreement, a risk to users or the service, or a legal requirement. Certain information may be retained where required by law or reasonably necessary for security, fraud prevention, enforcement, or dispute resolution.</p>

      <h2>9. Third-Party Services</h2>
      <p>Leyna may make third-party content or services available. Those third parties may apply their own terms and privacy policies. To the extent permitted by law, Leyna is not responsible for third-party content, availability, or practices.</p>

      <h2>10. Availability and Disclaimers</h2>
      <p>Leyna may change, be interrupted, or become unavailable. To the extent permitted by law, Leyna is provided “as is” and “as available,” without warranties that it will be uninterrupted, error-free, secure, or suitable for every purpose. User content reflects the views of its author, and you are responsible for evaluating it.</p>

      <h2>11. Limitation of Liability</h2>
      <p>To the extent permitted by law, Leyna and its operators will not be liable for indirect, incidental, special, consequential, exemplary, or punitive losses arising from or related to your use of the service. Nothing in this Agreement excludes or limits liability that cannot lawfully be excluded or limited.</p>

      <h2>12. Changes and General Terms</h2>
      <p>We may update this Agreement to reflect legal, safety, or service changes. The updated version applies from the effective date shown when it is made available. If any provision is unenforceable, the remaining provisions remain effective. A failure to enforce a provision is not a waiver of it.</p>

      <h2>13. Contact</h2>
      <p>For questions, reports, appeals, or account-related requests, contact <a href="mailto:support@leyna.com">support@leyna.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'LeynaUserAgreement'
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
