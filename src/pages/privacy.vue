<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Tigoo Privacy Policy</h1>

      <p class="effective-date"><strong>Effective Date: July 1, 2026</strong></p>

      <p>
        This Privacy Policy explains how Tigoo ("we", "our", or "us") collects, uses, stores, shares, and protects information when you use
        our mobile application, equestrian journey logging features, route sharing tools, messaging features, account features, and related services.
      </p>

      <p>
        By using Tigoo, you agree to the collection and use of information as described in this Privacy Policy.
        If you do not agree, please do not use Tigoo. We are committed to protecting your privacy in full compliance with the Apple App Store Review Guidelines.
      </p>

      <h2>1. Information We Collect</h2>
      <p>
        We collect information you provide, information generated when you capture and share your equestrian moments, and technical data strictly needed
        to operate our communication and social features.
      </p>

      <h2>2. Account Information</h2>
      <p>
        When you register, sign in, or update your profile, we may collect your mobile phone number, third-party login credentials, 
        account identifiers, profile photo, avatar, nickname, and app identifiers. This information is used to establish your equestrian identity and 
        secure your trusted social circle.
      </p>

      <h2>3. Media, Routes, and Location Data (Optional)</h2>
      <p>
        Tigoo is designed to document your equestrian journey through short videos, photos, and reflections. We request explicit permission to access your device's 
        camera and photo library to let you share daily routine updates, breakthroughs in training, and scenic views along the trail. 
      </p>
      <p>
        If you utilize our route-sharing features to record your rides or explore trails, we may request access to your device's location data. 
        We prioritize local storage architectures on your device to enhance your data security and autonomy. Your route data is only shared with the community when you actively choose to do so.
      </p>

      <h2>4. User Content and Communications</h2>
      <p>
        Tigoo processes content you send, receive, or interact with, including one-on-one chats, group conversations, posts, comments, reports, block actions, 
        messages, timestamps, and sender/recipient identifiers to foster an authentic and secure equestrian community.
      </p>

      <h2>5. Payment and Subscription Information</h2>
      <p>
        Tigoo may support premium subscriptions or paid features through Apple In-App Purchase (IAP). Apple processes all payment details, and Tigoo does not 
        receive or store your full payment card or financial details. We only receive transaction status and product identifiers required to activate your premium features.
      </p>

      <h2>6. Device, Usage, and Technical Information</h2>
      <p>
        To ensure application stability and service security, we may collect device type, operating system version, app version, language, permitted device
        identifiers, IP address, timestamps, request logs, crash logs, diagnostics, and security events.
      </p>

      <h2>7. How We Use Information</h2>
      <p>
        We use information to create and secure accounts, display your equestrian logs, provide route-sharing and messaging features, save login status, 
        handle user reports, block users, prevent abuse, improve application performance, and comply with legal, security, and App Store platform requirements.
      </p>

      <h2>8. How We Share Information</h2>
      <p>
        We do not sell, rent, or trade your personal information. We may share information with essential service providers (such as hosting infrastructure), 
        Apple, or law enforcement authorities when strictly required by applicable laws or regulations.
      </p>

      <h2>9. Data Storage, Security, and Privacy Controls</h2>
      <p>
        We use robust technical and organizational measures to safeguard your data. To maximize user autonomy and data privacy, Tigoo prioritizes local storage architectures 
        on your device for core records where feasible. 
      </p>
      <p>
        You hold full control over your privacy settings. You may revoke camera, photo library, location, or tracking permissions anytime via your iOS system settings.
      </p>

      <h2>10. Account Deletion and Data Retention</h2>
      <p>
        We keep information for as long as needed to maintain accounts, provide services, and support security. <strong>You can completely and permanently delete your account 
        at any time via the app settings (Settings > Account Security > Delete Account).</strong> Account deletion is an irreversible action; once processed, all your personal data, 
        cloud records, shared routes, and association tokens will be permanently erased immediately.
      </p>

      <h2>11. Children and Minors</h2>
      <p>
        Tigoo is designed for a trusted equestrian community among individuals who meet the legal age requirements in their respective regions. We do not knowingly collect personal 
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
        <strong>Email: Tigoouser@gmail.com</strong>
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'TigooPrivacyPolicy'
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