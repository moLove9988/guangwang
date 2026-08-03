<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Vimua Terms of Service</h1>

      <p>
        Welcome to Vimua! By accessing or using our mobile application, website, or services (collectively, "Vimua" or
        the "Platform"), you agree to comply with and be bound by the following Terms of Service ("Terms"). Please read
        them carefully.
      </p>

      <h2>1. Eligibility</h2>
      <p>
        You must be at least 13 years old (or the minimum legal age in your jurisdiction) to use Vimua. If you are
        under 18, you may only use the Platform with the consent and supervision of a parent or legal guardian.
      </p>

      <h2>2. Your Account</h2>
      <p>
        To access certain features, you must create an account. You are responsible for maintaining the confidentiality
        of your login credentials and for all activities that occur under your account.
      </p>
      <p>You agree that:</p>
      <ul>
        <li>Your profile information is accurate and up-to-date.</li>
        <li>You will not impersonate any person or entity.</li>
        <li>You will not create multiple accounts for disruptive or fraudulent purposes.</li>
      </ul>

      <h2>3. User Content</h2>
      <p>
        You may livestream, post photos, videos, comments, and other content ("User Content") on Vimua. By doing so,
        you grant Vimua a worldwide, non-exclusive, royalty-free license to use, display, reproduce, and distribute
        your content in connection with the operation and promotion of the Platform.
      </p>
      <p>You agree not to post or stream content that:</p>
      <ul>
        <li>Is unlawful, harmful, threatening, abusive, harassing, defamatory, vulgar, obscene, or hateful;</li>
        <li>Infringes on the intellectual property or privacy rights of others;</li>
        <li>Contains false or misleading information;</li>
        <li>Includes unauthorized commercial or promotional content, unless permitted by Vimua.</li>
      </ul>

      <h2>4. Livestreaming &amp; Selling Products</h2>
      <p>
        Vimua allows users to host livestreams, demonstrate beauty routines, and promote or sell products. As a
        livestreamer or seller:
      </p>
      <ul>
        <li>
          You are responsible for ensuring your claims and endorsements are truthful and comply with applicable laws.
        </li>
        <li>You must comply with local regulations regarding online sales, product safety, and advertising.</li>
      </ul>
      <p>
        Vimua is not liable for transactions between users unless explicitly stated otherwise.
      </p>

      <h2>5. Community Guidelines</h2>
      <p>We value respectful and positive engagement. You agree to:</p>
      <ul>
        <li>Treat others with kindness and respect;</li>
        <li>Refrain from hate speech, harassment, or any harmful behavior;</li>
        <li>Report content that violates these Terms or community standards.</li>
      </ul>

      <h2>6. Intellectual Property</h2>
      <p>
        All content and features provided by Vimua (excluding User Content) are owned by or licensed to Vimua. You may
        not reproduce, distribute, or create derivative works without our written permission.
      </p>

      <h2>7. Privacy</h2>
      <p>
        Your use of Vimua is also governed by our Privacy Policy, which outlines how we collect, use, and protect your
        personal data.
      </p>

      <h2>8. Termination</h2>
      <p>
        We reserve the right to suspend or terminate your access to Vimua at any time if you violate these Terms or
        engage in harmful conduct. We may also remove content that violates our policies.
      </p>

      <h2>9. Disclaimers</h2>
      <p>
        Vimua is provided "as is" and "as available." We do not guarantee uninterrupted service or that the Platform
        will meet your expectations. You use Vimua at your own risk.
      </p>

      <h2>10. Limitation of Liability</h2>
      <p>
        To the fullest extent permitted by law, Vimua and its affiliates shall not be liable for any indirect,
        incidental, special, or consequential damages arising from your use of the Platform.
      </p>

      <h2>11. Changes to Terms</h2>
      <p>
        We may update these Terms from time to time. Continued use of Vimua after such changes constitutes your
        acceptance of the updated Terms.
      </p>

      <h2>12. Contact Us</h2>
      <p>For any questions or concerns regarding these Terms, please contact us at:</p>
      <p>Email: vimua@gmail.com</p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'VimuaUserAgreement'
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

  p {
    font-size: 14px;
  }

  ul {
    font-size: 14px;
  }
}
</style>
