<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Barb Privacy Policy</h1>

      <p class="effective-date"><strong>Effective Date: July 1, 2026</strong></p>

      <p>
        This Privacy Policy explains how Barb ("we", "our", or "us") collects, uses, stores, shares, and protects information when you use
        our mobile application, AI-assisted reply features, messaging features, account features, and related services.
      </p>

      <p>
        By using Barb, you agree to the collection and use of information as described in this Privacy Policy.
        If you do not agree, please do not use Barb. We are committed to protecting your privacy in full compliance with the Apple App Store Review Guidelines.
      </p>

      <h2>1. Information We Collect</h2>
      <p>
        We collect information you provide, information generated when you use Barb, and information strictly needed
        to operate our communication and AI-assisted features.
      </p>

      <h2>2. Account Information</h2>
      <p>
        When you register, sign in, or update your profile, we may collect your mobile phone number, third-party login credentials, 
        account identifiers, profile photo, avatar, nickname, and app identifiers. This information is used to establish your identity and 
        secure your trusted messaging circle.
      </p>

      <h2>3. Contacts Information (Optional)</h2>
      <p>
        Barb is built for familiar connections in a trusted space. We may request explicit permission to access your device's address book/contacts 
        to help you discover and add known contacts. We do not upload or store your contacts for marketing purposes, and we only process this data 
        with your direct and explicit consent.
      </p>

      <h2>4. User Content, Communications, and AI processing</h2>
      <p>
        Barb processes content you send, receive, or interact with, including one-on-one chats, group conversations, reports, block actions, 
        messages, timestamps, and sender/recipient identifiers. 
      </p>
      <p>
        When you utilize our "AI Quick Reply" feature, the conversation context is processed to generate helpful response suggestions in different tones. 
        <strong>All conversation data processed for AI generation is handled immediately. Other than temporary local caching on your device, we do not 
        store, share, or use your chat text to train cross-user AI models or monetize your data.</strong>
      </p>

      <h2>5. Payment and Purchase Information</h2>
      <p>
        Barb may support subscriptions or paid features through Apple In-App Purchase (IAP). Apple processes all payment details, and Barb does not 
        receive or store your full payment card or financial details. We only receive transaction status and product identifiers required to activate your features.
      </p>

      <h2>6. Device, Usage, and Technical Information</h2>
      <p>
        To ensure application stability and service security, we may collect device type, operating system version, app version, language, permitted device
        identifiers, IP address, timestamps, request logs, crash logs, diagnostics, and security events.
      </p>

      <h2>7. How We Use Information</h2>
      <p>
        We use information to create and secure accounts, provide AI-assisted replies and messaging features, save login status, display content, 
        handle user reports, block users, prevent abuse, improve application performance, and comply with legal, security, and App Store platform requirements.
      </p>

      <h2>8. How We Share Information</h2>
      <p>
        We do not sell, rent, or trade your personal information. We may share information with essential service providers (such as hosting infrastructure), 
        Apple, or law enforcement authorities when strictly required by applicable laws or regulations.
      </p>

      <h2>9. Data Storage, Security, and Privacy Controls</h2>
      <p>
        We use robust technical and organizational measures to safeguard your data. To maximize user autonomy and data privacy, Barb prioritizes local storage architectures 
        on your device for core messaging records. 
      </p>
      <p>
        You hold full control over your privacy settings. You may revoke camera, photo library, or contact permissions anytime via your iOS system settings.
      </p>

      <h2>10. Account Deletion and Data Retention</h2>
      <p>
        We keep information for as long as needed to maintain accounts, provide services, and support security. <strong>You can completely and permanently delete your account 
        at any time via the app settings (Settings > Account Security > Delete Account).</strong> Account deletion is an irreversible action; once processed, all your personal data, 
        cloud records, and association tokens will be permanently erased immediately.
      </p>

      <h2>11. Children and Minors</h2>
      <p>
        Barb is designed for trusted everyday communication among individuals who meet the legal age requirements in their respective regions. We do not knowingly collect personal 
        information from minors under the age of 18 without appropriate parental or guardian supervision and consent.
      </p>

      <h2>12. Changes to This Privacy Policy</h2>
      <p>
        We may update this Privacy Policy from time to time. Material updates will be clearly notified within the application. The updated version will apply immediately when posted.
      </p>

      <h2>13. Contact</h2>
      <p>
        If you have questions about this Privacy Policy or your privacy choices, please contact our dedicated support team via:
        <br />
        <strong>Email: barb@gmail.com</strong>
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'BarbPrivacyPolicy'
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