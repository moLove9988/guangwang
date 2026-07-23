<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Eilune User Agreement</h1>
      <p class="effective-date"><strong>Effective Date: July 23, 2026</strong></p>
      <p>This User Agreement governs your access to and use of Eilune and any related services we make available.</p>
      <p>By accessing or using Eilune, you agree to this User Agreement and the Privacy Policy. If you do not agree, you must not use Eilune.</p>

      <h2>1. Using Eilune</h2>
      <p>You may use Eilune only if you can legally agree to these terms and your use is permitted by applicable law. You are responsible for complying with the laws and rules that apply to you.</p>

      <h2>2. Accounts</h2>
      <p>You agree to provide accurate information, keep your account details secure, and promptly update information that changes. You are responsible for activity associated with your account.</p>
      <p>You may not sell or transfer an account, impersonate another person, create an account through deceptive means, or use another person's account without permission.</p>

      <h2>3. Your Content</h2>
      <p>You retain ownership of content you submit. You must have all rights and permissions needed to submit that content, including permission from anyone shown, heard, quoted, or identified in it.</p>
      <p>You grant Eilune a worldwide, non-exclusive, royalty-free license to host, reproduce, format, display, and distribute your content only as needed to provide the service, honor your sharing choices, promote safety, and enforce these terms. This license ends when the content is deleted, except where continued retention is required by law or reasonably necessary to resolve a report or dispute.</p>

      <h2>4. Community Rules</h2>
      <p>You must treat others respectfully and must not submit, request, encourage, or distribute content or conduct that is unlawful, fraudulent, threatening, harassing, hateful, discriminatory, sexually explicit, exploitative, violent, invasive of privacy, deceptive, or otherwise harmful.</p>
      <p>You must not infringe intellectual-property or other rights, reveal another person's private information without permission, impersonate others, spam, manipulate engagement, distribute malicious material, evade restrictions, interfere with the service, or misuse reporting and safety controls.</p>

      <h2>5. Reporting, Blocking, and Moderation</h2>
      <p>You may report content or conduct that you believe violates these terms, block another user, or contact us using the information below. We review reports and may remove or restrict content, limit interactions, suspend or terminate access, preserve relevant information, or take other appropriate action.</p>
      <p>We may act when reasonably necessary to enforce these terms, protect users or rights, respond to safety concerns, or comply with law. Serious or repeated violations may result in permanent loss of access.</p>

      <h2>6. Eilune Materials</h2>
      <p>Eilune and its names, logos, designs, text, graphics, and other materials are protected by intellectual-property laws. Subject to these terms, you receive a limited, personal, revocable, non-exclusive, and non-transferable right to use Eilune for lawful purposes.</p>

      <h2>7. Purchases and Digital Items</h2>
      <p>Optional purchases are processed by Apple and are also subject to the terms presented at purchase and Apple's applicable terms. Digital items are licensed, not sold, have no cash value, and may not be sold or transferred outside Eilune.</p>
      <p>Apple controls payment processing and refund decisions. Deleting an Eilune account does not delete records maintained independently by Apple.</p>

      <h2>8. Suspension and Account Deletion</h2>
      <p>You may initiate permanent account deletion from the account settings. Account deletion removes the account and associated personal information and content, except information that must be retained by law or is reasonably necessary for security, fraud prevention, or resolving disputes.</p>
      <p>We may suspend or terminate access for a violation of these terms, a risk to users or the service, or a legal requirement. Where appropriate, we may provide notice or an opportunity to appeal by contacting support.</p>

      <h2>9. Availability and Disclaimers</h2>
      <p>Eilune may change, be interrupted, or become unavailable. To the extent permitted by law, Eilune is provided “as is” and “as available,” without warranties that it will be uninterrupted, error-free, or suitable for every purpose.</p>
      <p>Content made available by users reflects their own views. You are responsible for evaluating content and for decisions you make based on it.</p>

      <h2>10. Limitation of Liability</h2>
      <p>To the extent permitted by law, Eilune and its operators will not be liable for indirect, incidental, special, consequential, or punitive loss arising from your use of the service. Nothing in these terms excludes or limits liability that cannot lawfully be excluded or limited.</p>

      <h2>11. Changes and General Terms</h2>
      <p>We may update these terms to reflect legal, safety, or service changes. The updated version applies from the effective date shown when it is made available. Continued use after that date constitutes acceptance where permitted by law.</p>
      <p>If any provision is unenforceable, the remaining provisions remain effective. A failure to enforce a provision is not a waiver of it.</p>

      <h2>12. Contact</h2>
      <p>For questions, reports, appeals, or account-related requests, contact <a href="mailto:support@eilune.com">support@eilune.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'EiluneUserAgreement'
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
