<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Womi Terms of Service</h1>

      <p class="effective-date"><strong>Effective Date: July 24, 2026</strong></p>

      <p>
        Welcome to Womi. By creating an account or using the App, you agree to these Terms.
      </p>

      <p>
        Womi is available worldwide except Mainland China. You are responsible for following the laws of your
        country or region.
      </p>

      <h2>1. Your Account</h2>
      <p>
        You must provide accurate information and keep your account secure. You are responsible for all activity
        under your account.
      </p>
      <p>
        You may not impersonate others, share accounts, or use Womi for illegal purposes.
      </p>

      <h2>2. User Content</h2>
      <p>
        You may post photos, videos, artwork, comments, messages, and other content.
      </p>
      <p>
        You must own your content or have permission to use it. You remain responsible for everything you publish
        or send through Womi.
      </p>
      <p>
        By posting content, you allow Womi to store, display, and process it as needed to operate the App.
      </p>

      <h2>3. Prohibited Content</h2>
      <p>You must not post or share content that is:</p>
      <ul>
        <li>Illegal, fraudulent, or misleading;</li>
        <li>Abusive, threatening, hateful, or discriminatory;</li>
        <li>Sexually explicit or harmful to minors;</li>
        <li>Violent, dangerous, or encouraging self-harm;</li>
        <li>Infringing copyright, privacy, or other rights;</li>
        <li>Spam, malware, scams, or unauthorised advertising;</li>
        <li>Encouraging vandalism, property damage, or other unlawful activity.</li>
      </ul>
      <p>
        Womi may remove prohibited content without prior notice.
      </p>

      <h2>4. Safety and Enforcement</h2>
      <p>
        Users may report or block accounts and content.
      </p>
      <p>
        Womi may review reports, remove content, limit features, suspend accounts, or permanently terminate accounts
        that violate these Terms or create safety risks.
      </p>
      <p>
        Serious illegal activity may be reported to the appropriate authorities.
      </p>

      <h2>5. AI Features</h2>
      <p>
        Womi AI provides creative suggestions for inspiration only.
      </p>
      <p>
        AI-generated results may be inaccurate or unsuitable. You are responsible for reviewing and using them
        appropriately.
      </p>

      <h2>6. Service Availability</h2>
      <p>
        Womi may update, restrict, suspend, or discontinue features when necessary.
      </p>
      <p>
        The App is provided on an "as is" basis. We do not guarantee uninterrupted or error-free service.
      </p>

      <h2>7. Changes to These Terms</h2>
      <p>
        We may update these Terms when our services, rules, or legal requirements change.
      </p>
      <p>
        Continued use of Womi after an update means you accept the revised Terms.
      </p>

      <h2>8. Contact Us</h2>
      <p>
        For questions, complaints, or safety concerns, contact:
      </p>
      <p>
        womi@gmail.com
      </p>
      <p>
        By using Womi, you confirm that you have read and agreed to these Terms of Service.
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'WomiTermsOfService'
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
