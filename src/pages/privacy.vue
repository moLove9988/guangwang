<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Vimua Privacy Policy</h1>

      <p>
        At Vimua, your privacy is important to us. This Privacy Policy explains how we collect, use, share, and protect
        your personal information when you use our app, website, and services (collectively, "Vimua" or the "Platform").
      </p>
      <p>
        By using Vimua, you agree to the practices described in this Privacy Policy.
      </p>

      <h2>1. Information We Collect</h2>
      <h3>a. Information You Provide:</h3>
      <ul>
        <li>Account Details: Username, email address, password, profile photo, bio, etc.</li>
        <li>Livestream Content: Video and audio content you broadcast or upload.</li>
        <li>Social Interactions: Messages, comments, likes, and video chats.</li>
        <li>
          Commerce Data: If you sell or buy products, we may collect shipping addresses, purchase history, and
          payment-related info (handled by third-party processors).
        </li>
        <li>User Support: Info provided when contacting customer service.</li>
      </ul>
      <h3>b. Automatically Collected Data:</h3>
      <ul>
        <li>Device Information: Device model, operating system, IP address, mobile network, and device identifiers.</li>
        <li>Usage Data: App interactions, viewed content, session duration, crash logs, etc.</li>
        <li>
          Location Data: Approximate location based on IP address or precise location if you enable GPS.
        </li>
      </ul>

      <h2>2. How We Use Your Information</h2>
      <p>We use your information to:</p>
      <ul>
        <li>Provide and improve Vimua's features and services.</li>
        <li>Personalize your experience (e.g., content suggestions, relevant livestreams).</li>
        <li>Enable livestreaming, social interaction, and product promotion/sales.</li>
        <li>Send important updates, promotional messages, and service notifications.</li>
        <li>Prevent fraud and ensure platform safety.</li>
        <li>Comply with legal obligations.</li>
      </ul>

      <h2>3. How We Share Your Information</h2>
      <p>We may share your data:</p>
      <ul>
        <li>
          With other users: Your profile and public content (posts, streams, comments) are visible to other users.
        </li>
        <li>
          With service providers: Such as cloud hosting, payment processors, analytics tools, and content moderation.
        </li>
        <li>For legal reasons: To comply with laws, enforce terms, or respond to lawful requests.</li>
        <li>
          In business transfers: In the event of a merger, acquisition, or asset sale, your data may be transferred.
        </li>
      </ul>

      <h2>4. Your Privacy Choices</h2>
      <p>You can:</p>
      <ul>
        <li>Edit or delete your profile information.</li>
        <li>Control notification and location settings in your device/app settings.</li>
        <li>Delete your account by contacting our support team.</li>
      </ul>

      <h2>5. Data Retention</h2>
      <p>
        We retain your data as long as necessary for the purposes outlined in this policy. If you delete your account,
        we will delete your personal information, except where retention is required by law.
      </p>

      <h2>6. Security</h2>
      <p>
        We implement industry-standard measures to protect your information. However, no system is 100% secure. Please
        use strong passwords and safeguard your login credentials.
      </p>

      <h2>7. Children's Privacy</h2>
      <p>
        Vimua is not intended for users under 13. If we learn we have collected data from a child without parental
        consent, we will delete it.
      </p>

      <h2>8. International Users</h2>
      <p>
        By using Vimua, you acknowledge that your data may be transferred to and processed in countries outside your
        own, including where data protection laws may differ.
      </p>

      <h2>9. Changes to This Policy</h2>
      <p>
        We may update this Privacy Policy from time to time. When we do, we'll notify you via the app or email.
        Continued use of Vimua constitutes your acceptance of the revised policy.
      </p>

      <h2>10. Contact Us</h2>
      <p>If you have any questions or requests regarding your privacy, please contact us at:</p>
      <p>Email: vimua@gmail.com</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'VimuaPrivacyPolicy'
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

h3 {
  margin: 18px 0 8px;
  font-size: 16px;
  font-weight: 700;
  line-height: 1.4;
  color: #111111;
}

p {
  margin: 0 0 14px;
  font-size: 15px;
  color: #333333;
}

ul {
  margin: 0 0 14px 20px;
  padding: 0;
  font-size: 15px;
  color: #333333;
}

li {
  margin: 0 0 8px;
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

  h3 {
    font-size: 15px;
  }

  p {
    font-size: 14px;
  }

  ul {
    font-size: 14px;
  }
}
</style>
