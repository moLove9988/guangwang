<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Livtoik Privacy Policy</h1>

      <p class="effective-date"><strong>Effective Date: June 23, 2026</strong></p>

      <p>
        This Privacy Policy explains how Livtoik collects, uses, stores, shares, and protects information when you use
        our mobile application, livestream features, H5 pages, messaging features, account features, purchases,
        and related services.
      </p>

      <p>
        By using Livtoik, you agree to the collection and use of information as described in this Privacy Policy.
        If you do not agree, please do not use Livtoik.
      </p>

      <h2>1. Information We Collect</h2>
      <p>
        We collect information you provide, information generated when you use Livtoik, and information needed
        to operate app features.
      </p>

      <h2>2. Account Information</h2>
      <p>
        When you register, sign in, or update your profile, we may collect your name, nickname, email address,
        password-related login credentials, account identifiers, profile photo, avatar, bio, profile settings,
        login token, verification status, and app identifiers.
      </p>

      <h2>3. User Content and Communications</h2>
      <p>
        Livtoik may collect and process content you create, upload, send, receive, or interact with, including
        livestream room information, challenge posts, activity posts, images, videos, comments, likes, join or cancel
        states, reports, block actions, messages, conversation information, timestamps, sender and recipient identifiers,
        and related metadata.
      </p>

      <h2>4. Camera, Photos, and Face Verification</h2>
      <p>
        Livtoik may request access to your camera or photo library for features such as profile images, activity covers,
        challenge covers, livestream features, and identity or age verification.
      </p>
      <p>
        If you use face verification, we may process a selfie or image to verify your identity, age, account integrity,
        or eligibility for app features. We use verification data to help protect users, prevent misuse,
        and support compliance.
      </p>

      <h2>5. Payment and Purchase Information</h2>
      <p>
        Livtoik may support purchases through Apple in-app purchase or H5-triggered purchase flows. We may receive
        transaction status, product identifiers, purchase results, balance updates, and related records needed to provide
        purchased features or virtual items.
      </p>
      <p>
        Apple processes payment details. Livtoik does not receive your full payment card information from Apple.
      </p>

      <h2>6. Device, Usage, and Technical Information</h2>
      <p>
        We may collect device type, operating system, app version, language, region, network state, permitted device
        identifiers, IP address, timestamps, request logs, API activity, H5 events, crash logs, diagnostics, feature usage,
        page visits, button actions, loading states, error messages, and security events.
      </p>

      <h2>7. Location and Address Information</h2>
      <p>
        Livtoik may allow you to enter event addresses, activity locations, delivery addresses, or other location-related
        information through app or H5 pages. We use this information to provide the feature you requested.
      </p>
      <p>
        Livtoik does not need precise device location unless a specific feature requests it and you grant that permission.
      </p>

      <h2>8. How We Use Information</h2>
      <p>
        We use information to create and secure accounts, provide livestreams, messaging, profiles, posts, challenges,
        H5 pages, purchases and settings, display content, save login status and preferences, process purchases,
        review content, handle reports, block users, prevent abuse, improve performance, diagnose issues, and comply
        with legal, security, App Store, and platform requirements.
      </p>

      <h2>9. How We Share Information</h2>
      <p>
        We may share information with service providers, payment providers, Apple, other users when you choose to interact
        publicly or directly, authorities when required by law, and parties involved in a business transfer.
      </p>
      <p>
        We do not sell your personal information in the ordinary meaning of selling it for money.
      </p>

      <h2>10. Data Storage and Security</h2>
      <p>
        We use reasonable technical and organizational measures to protect information. However, no method of transmission
        or storage is completely secure.
      </p>
      <p>
        Some information may be stored locally on your device, such as login state, token data, user lists,
        blocked user IDs, local challenge posts, and preferences.
      </p>

      <h2>11. Data Retention</h2>
      <p>
        We keep information for as long as needed to provide Livtoik, maintain accounts, comply with legal obligations,
        resolve disputes, prevent abuse, enforce agreements, support security, and operate business records.
      </p>

      <h2>12. Your Choices and Rights</h2>
      <p>
        Depending on your location, you may have rights to access, correct, delete, or receive a copy of certain personal
        information, or to object to or restrict certain processing.
      </p>
      <p>
        You can revoke camera or photo permissions in your device settings. If you revoke permissions, related features
        may stop working.
      </p>

      <h2>13. Children and Minors</h2>
      <p>
        Livtoik is not intended for children who are not old enough to legally use the service in their location.
        We do not knowingly collect personal information from children without appropriate consent where required.
      </p>

      <h2>14. International Processing</h2>
      <p>
        Your information may be processed or stored in countries or regions other than where you live.
        Data protection laws may differ from those in your location.
      </p>

      <h2>15. Changes to This Privacy Policy</h2>
      <p>
        We may update this Privacy Policy from time to time. The updated version will apply when posted or made available
        in the app.
      </p>

      <h2>16. Contact</h2>
      <p>
        If you have questions about this Privacy Policy or your privacy choices, please contact us through the in-app
        support or settings page.
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'LivtoikPrivacyPolicy'
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
