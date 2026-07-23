<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Antje User Agreement</h1>
      <p class="effective-date"><strong>Effective Date: July 21, 2026</strong></p>
      <p>This User Agreement (the “Agreement”) governs your access to and use of Antje (the “Service”). By creating an account or using the Service, you agree to this Agreement and acknowledge the Privacy Policy. If you do not agree, do not use the Service.</p>

      <h2>1. Acceptance and Legal Capacity</h2>
      <p>You may use the Service only if applicable law permits you to do so and you have the legal authority to accept this Agreement. If authorization is required under applicable law, the appropriate responsible person must provide it.</p>

      <h2>2. Accounts</h2>
      <p>You agree to provide accurate information, keep your account secure, and notify us if you believe it has been used without permission. You may not sell, transfer, lend, or misuse an account.</p>
      <p>You may delete your account through the account controls or request assistance by contacting us. Information may be retained only as described in the Privacy Policy or as required by law.</p>

      <h2>3. Community Standards</h2>
      <p>Antje is intended for courteous and respectful interaction. You must respect the dignity, privacy, safety, personal boundaries, intellectual property, and differing opinions of others. You are responsible for the content you provide and for your conduct.</p>
      <p>We do not tolerate abusive users or objectionable content. Threats, harassment, bullying, stalking, exploitation, discrimination, impersonation, and conduct that deliberately endangers another person are prohibited.</p>

      <h2>4. User Content</h2>
      <p>You represent that you have the rights and permissions necessary for any content you provide and that your content does not violate applicable law or another person’s rights.</p>
      <p>You retain ownership of your content. You grant us a non-exclusive, worldwide, royalty-free license to host, reproduce, process, display, and distribute it only as reasonably necessary to provide the Service, make it available to the audience you select, maintain safety, and enforce this Agreement.</p>

      <h2>5. Prohibited Conduct</h2>
      <p>You may not provide unlawful, sexually exploitative, pornographic, hateful, threatening, graphically violent, fraudulent, deceptive, defamatory, harassing, invasive, or infringing content. Content that exploits or endangers protected persons is strictly prohibited.</p>
      <p>You may not disclose private information without permission, encourage self-harm or dangerous acts, distribute spam or malicious code, manipulate engagement, evade safety controls, abuse reporting tools, access another account without authorization, interfere with the Service, or use the Service to harm or exploit another person.</p>

      <h2>6. Safety, Reporting, and Enforcement</h2>
      <p>Use the available report and block controls if you encounter objectionable content or abusive conduct. You may also contact us at <a href="mailto:support@antje.com">support@antje.com</a>. Reports must be made honestly and include enough information to identify the concern.</p>
      <p>We may filter, restrict, or remove content; limit access to features; preserve relevant safety records; or suspend or terminate accounts when reasonably necessary to protect users, enforce this Agreement, or comply with law. We aim to address safety concerns within a reasonable period appropriate to their severity.</p>

      <h2>7. Digital Purchases</h2>
      <p>Any price and digital item will be shown before purchase. Unless applicable law requires otherwise, digital items have no cash value, may be used only within the Service, and may not be transferred or exchanged for cash. Purchases and refund requests are also subject to the terms of the applicable app marketplace.</p>

      <h2>8. Informational Content</h2>
      <p>Suggestions and informational content may be incomplete, inaccurate, or unsuitable for a particular situation. They are not medical, legal, financial, emergency, or other professional advice. Review information carefully before relying on or sharing it.</p>

      <h2>9. Intellectual Property</h2>
      <p>The names, logos, designs, text, images, software, and other elements associated with the Service are owned by us or their respective rights holders. This Agreement grants you only a limited, personal, non-exclusive, non-transferable right to use the Service lawfully.</p>

      <h2>10. Third-Party Services</h2>
      <p>Third-party products or services may be governed by their own terms and privacy policies. We are not responsible for content or services provided independently by third parties.</p>

      <h2>11. Account Restriction and Termination</h2>
      <p>We may restrict, suspend, or terminate an account in response to a serious or repeated violation, harm to another person, a safety risk, fraud, misuse, or a legal requirement. Where reasonable, we may provide notice of the reason.</p>

      <h2>12. Availability and Disclaimers</h2>
      <p>We may change, suspend, or discontinue all or part of the Service for quality, safety, legal, or other reasonable reasons. Except where required by law, we do not guarantee uninterrupted availability, complete accuracy, or suitability for every purpose.</p>

      <h2>13. Limitation of Liability</h2>
      <p>To the extent permitted by law, we are not liable for indirect, incidental, special, or consequential loss arising from use of, or inability to use, the Service. Nothing in this Agreement excludes liability that cannot lawfully be excluded.</p>

      <h2>14. Changes to This Agreement</h2>
      <p>We may update this Agreement to reflect changes in law or the Service. If a change is material, we will provide notice through this page or another appropriate method.</p>

      <h2>15. Contact Us</h2>
      <p>For questions about this Agreement, safety, or account deletion, contact <a href="mailto:support@antje.com">support@antje.com</a>.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'AntjeUserAgreement'
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
