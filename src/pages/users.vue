<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Saya User Agreement</h1>
      <p class="effective-date"><strong>Effective Date: July 21, 2026</strong></p>
      <p>This User Agreement governs your access to and use of Saya and its related services.</p>
      <p>By accessing or using Saya, you agree to this User Agreement and the Privacy Policy. If you do not agree, do not use Saya.</p>

      <h2>1. Acceptance and Eligibility</h2>
      <p>You must be legally able to enter into this agreement in your location. Minors may use Saya only as permitted by applicable law and, where required, with permission from a parent or legal guardian.</p>
      <p>You must use Saya in accordance with applicable laws and this User Agreement.</p>

      <h2>2. Account and Access</h2>
      <p>You agree to provide accurate information and are responsible for activity associated with your account.</p>
      <p>You may not sell, transfer, impersonate another person through, or misuse an account.</p>

      <h2>3. User Content</h2>
      <p>You retain ownership of content you create or submit. You must have all rights and permissions necessary to use that content, including permission from people shown or identified in it.</p>
      <p>You grant Saya a limited, non-exclusive permission to process, display, format, and make available your content only as reasonably necessary to provide the service, apply your visibility choices, maintain safety, and enforce this User Agreement.</p>

      <h2>4. Community Standards</h2>
      <p>Saya does not tolerate objectionable content or abusive conduct. You must treat others with respect and remain responsible for content and interactions you make available.</p>
      <p>You may not submit or promote unlawful, threatening, harassing, hateful, discriminatory, sexually explicit, violent, deceptive, infringing, invasive, or otherwise harmful content. You may not impersonate others, disclose another person's private information without permission, spam, interfere with the service, or misuse safety controls.</p>

      <h2>5. Reports, Blocking, and Enforcement</h2>
      <p>You may report inappropriate content, block abusive users, or contact support. Content or access may be restricted when reasonably necessary to protect users, enforce this User Agreement, or comply with law.</p>
      <p>Serious or repeated violations may result in removal of content or loss of access to Saya.</p>

      <h2>6. Intellectual Property</h2>
      <p>Saya and its names, logos, designs, text, software, and other service materials are owned by their respective rights holders. This User Agreement gives you only a limited, personal, non-exclusive, non-transferable right to use Saya for lawful purposes.</p>

      <h2>7. Purchases and Virtual Items</h2>
      <p>Optional digital items are offered through Apple's in-app purchase system and are subject to the terms shown at purchase. Virtual items have no cash value, may not be transferred outside Saya, and do not expire while the associated account remains available.</p>
      <p>Apple processes payments and determines refund eligibility under its policies and applicable law.</p>

      <h2>8. Acceptable Use</h2>
      <p>You may not attempt unauthorized access, circumvent access controls, disrupt Saya, distribute malicious code, exploit errors, manipulate purchases, or use Saya in a way that harms another person or the service.</p>

      <h2>9. Makeup Disclaimer</h2>
      <p>Saya provides creative content and tools, not medical, dermatological, allergy, or professional cosmetic advice. You are responsible for determining whether any product or technique is suitable for you.</p>

      <h2>10. Account Deletion</h2>
      <p>You may initiate permanent account deletion from the account settings. Deletion cannot be undone and is subject to any retention required by law or maintained independently by Apple.</p>

      <h2>11. Availability and Liability</h2>
      <p>Saya may change or become unavailable. To the extent permitted by law, Saya is provided without warranties that it will always be uninterrupted, error-free, or suitable for every purpose.</p>
      <p>To the extent permitted by law, Saya is not liable for indirect, incidental, special, or consequential loss. Nothing in this User Agreement limits liability that cannot lawfully be limited.</p>

      <h2>12. Changes and Contact</h2>
      <p>We may update this User Agreement to reflect changes in law or the service. The updated version applies from the effective date shown when it is made available.</p>
      <p>For questions about this User Agreement, safety, or account deletion, contact <a href="mailto:support@saya.com">support@saya.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'SayaUserAgreement'
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
