<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Womi Privacy Policy</h1>

      <p class="effective-date"><strong>Effective Date: July 24, 2026</strong></p>

      <p>
        Womi respects your privacy. This Privacy Policy explains how we collect, use, and protect your information
        when you use the Womi app.
      </p>

      <p>
        Womi is available worldwide except Mainland China.
      </p>

      <h2>1. Information We Collect</h2>
      <p>We may collect:</p>
      <ul>
        <li>Account information, such as your username, email address, profile photo, and interests;</li>
        <li>Content you upload, including photos, videos, comments, messages, and AI prompts;</li>
        <li>Device and usage information, such as device type, IP address, app activity, and crash data;</li>
        <li>Camera, photo library, microphone, notification, or location information with your permission.</li>
      </ul>

      <h2>2. How We Use Information</h2>
      <p>We use your information to:</p>
      <ul>
        <li>Create and manage your account;</li>
        <li>Provide posts, messages, recommendations, and AI features;</li>
        <li>Improve app performance and user experience;</li>
        <li>Prevent fraud, abuse, illegal activity, and prohibited content;</li>
        <li>Review reports and enforce our rules;</li>
        <li>Respond to support requests.</li>
      </ul>
      <p>
        We do not sell your personal information.
      </p>

      <h2>3. Sharing of Information</h2>
      <p>
        We may share limited information with trusted service providers that help us operate Womi, such as cloud
        hosting, analytics, notifications, content moderation, and AI services.
      </p>
      <p>
        We may also disclose information when required by law or necessary to protect users, Womi, or public safety.
      </p>
      <p>
        Public profile information and content you publish may be visible to other users.
      </p>

      <h2>4. User Content and Safety</h2>
      <p>
        Users must not publish illegal, abusive, hateful, violent, sexually explicit, fraudulent, infringing, or
        otherwise prohibited content.
      </p>
      <p>
        Womi may review, restrict, or remove content and suspend accounts that violate our rules.
      </p>

      <h2>5. Data Retention and Security</h2>
      <p>
        We keep information only for as long as necessary to provide the Service, maintain security, resolve disputes,
        and comply with legal obligations.
      </p>
      <p>
        We use reasonable measures to protect your information, but no online service can guarantee complete security.
      </p>

      <h2>6. Your Choices</h2>
      <p>
        You may update your profile, manage device permissions, or request access to, correction of, or deletion of
        your personal information.
      </p>
      <p>
        You may request account deletion through the App or by contacting us.
      </p>

      <h2>7. Children's Privacy</h2>
      <p>
        Womi is not intended for children below the minimum legal age required in their country or region.
      </p>
      <p>
        If we learn that an ineligible child has provided personal information, we may delete the information and
        close the account.
      </p>

      <h2>8. Contact Us</h2>
      <p>
        For privacy questions or requests, contact:
      </p>
      <p>
        womi@gmail.com
      </p>
      <p>
        By using Womi, you acknowledge that you have read and understood this Privacy Policy.
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'WomiPrivacyPolicy'
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

p,
li {
  font-size: 15px;
  color: #333333;
}

p {
  margin: 0 0 14px;
}

ul {
  margin: 0 0 14px 20px;
  padding: 0;
}

li {
  margin: 0 0 6px;
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

  p,
  li {
    font-size: 14px;
  }
}
</style>
