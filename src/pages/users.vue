<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Dollu Terms of Service</h1>
      <p class="effective-date">Effective Date: July 8, 2026</p>

      <p>Welcome to Dollu. These Terms of Service explain the rules for using Dollu, a community app for doll styling, collection records, outfit inspiration, creative notes, and AI Collector assistance. By using Dollu, you agree to these Terms.</p>

      <h2>1. Eligibility</h2>
      <p>You must meet the minimum age required by your local law and Apple platform rules to use Dollu. If you use Dollu on behalf of another person or organization, you confirm that you have authority to accept these Terms.</p>
      <p>Dollu is not a random, anonymous, adult, or borderline communication service. It is designed for hobby-based doll dressing, collection organization, and respectful community sharing.</p>

      <h2>2. Account Responsibilities</h2>
      <p>You are responsible for keeping your account credentials secure and for all activity under your account. You agree to provide accurate information and to update it when needed.</p>
      <p>You may not impersonate another person, misrepresent your identity, use another user’s account, or attempt to bypass security or moderation systems.</p>

      <h2>3. Dollu Services</h2>
      <p>Dollu lets users create doll looks, save outfit ideas, organize collection progress, share posts, react to community content, keep styling notes, and use AI Collector features for creative inspiration.</p>
      <p>Some features may change, pause, or be removed over time. We may also add safety limits, content rules, or account checks when necessary to protect the community.</p>

      <h2>4. User Content</h2>
      <p>You keep ownership of content you create, such as doll styling photos, short-form clips, collection notes, comments, and profile details. By submitting content to Dollu, you grant Dollu a non-exclusive, worldwide, royalty-free license to host, display, process, adapt for formatting, and distribute that content only as needed to operate and improve the service.</p>
      <p>You confirm that you have the rights needed to submit your content and that your content does not violate law, these Terms, or the rights of others.</p>

      <h2>5. Community Rules</h2>
      <p>You agree not to submit or promote content involving child exploitation, sexual content involving minors, sexual solicitation, harassment, hate, threats, graphic violence, self-harm encouragement, illegal activity, privacy invasion, doxxing, spam, malware, impersonation, fraud, or intellectual property infringement.</p>
      <p>You agree not to use Dollu for dating-style solicitation, adult services, anonymous harmful conduct, or unrelated commercial activity. Dollu must remain focused on doll styling, collecting, creativity, and respectful hobby discussion.</p>

      <h2>6. Reports, Blocking, and Enforcement</h2>
      <p>Dollu provides reporting and blocking tools to support a safer community. We may review reported content, remove content, limit visibility, restrict features, suspend accounts, or terminate access when we believe these Terms have been violated.</p>
      <p>We may also act when conduct creates legal risk, safety risk, technical harm, or a poor experience for other Dollu users.</p>

      <h2>7. AI Collector Features</h2>
      <p>AI Collector features may provide outfit prompts, styling suggestions, trend ideas, and organization notes. These outputs are for creative inspiration only. You are responsible for reviewing AI outputs before relying on or sharing them.</p>
      <p>You may not use AI features to create or promote prohibited content, impersonation, harassment, or other harmful activity.</p>

      <h2>8. Optional Digital Add-ons</h2>
      <p>If Dollu offers optional digital add-ons inside the iOS app, the related Apple-managed flow will apply where required by Apple rules. Digital add-ons have no cash value, are not transferable outside Dollu, and may be limited by account status, availability, or platform rules.</p>

      <h2>9. Privacy</h2>
      <p>Your use of Dollu is also governed by our Privacy Policy, which explains how we collect and use information. Please review it carefully.</p>

      <h2>10. Third-Party Services</h2>
      <p>Dollu may link to or integrate platform services or external pages. We are not responsible for third-party content, policies, or practices. Your use of third-party services may be governed by their own terms.</p>

      <h2>11. Service Availability</h2>
      <p>We aim to keep Dollu reliable, but we do not guarantee that the service will always be available, uninterrupted, secure, or error-free. We may perform maintenance, apply updates, or limit features when necessary.</p>

      <h2>12. Termination</h2>
      <p>You may stop using Dollu at any time. We may suspend or terminate access if you violate these Terms, create safety risk, misuse the service, or if continued access would create legal or technical risk.</p>

      <h2>13. Disclaimers and Liability</h2>
      <p>Dollu is provided on an “as is” and “as available” basis. To the fullest extent allowed by law, we disclaim warranties that are not expressly stated in these Terms.</p>
      <p>To the fullest extent allowed by law, Dollu and its operators will not be liable for indirect, incidental, special, consequential, or punitive damages arising from your use of the service.</p>

      <h2>14. Changes to These Terms</h2>
      <p>We may update these Terms from time to time. If changes are material, we will provide notice in the app or through another reasonable method. Continued use of Dollu after the update means you accept the updated Terms.</p>

      <h2>15. Contact Us</h2>
      <p>If you have questions about these Terms, account access, safety issues, or community reports, please contact us at Dollu@gmail.com.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'DolluUserAgreement'
}
</script>

<style scoped>
.agreement-page {
  padding: 24px;
  background: #f9f9fb;
  color: #333;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.7;
}

.agreement-section {
  max-width: 860px;
  margin: 0 auto;
  background: #fff;
  border-radius: 16px;
  padding: 32px;
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.06);
}

h1 {
  font-size: 28px;
  margin-bottom: 8px;
  color: #111;
}

h2 {
  font-size: 20px;
  margin-top: 28px;
  color: #222;
}

p {
  font-size: 15px;
  margin: 12px 0;
}

.effective-date {
  color: #777;
  font-size: 14px;
  margin-bottom: 24px;
}

@media screen and (max-width: 600px) {
  .agreement-page {
    padding: 16px;
  }

  .agreement-section {
    padding: 22px;
  }

  h1 {
    font-size: 24px;
  }

  h2 {
    font-size: 18px;
  }
}
</style>
