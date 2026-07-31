<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Tolmi User Agreement</h1>

      <p class="effective-date"><strong>Effective Date: July 31, 2026</strong></p>

      <p>
        Welcome to Tolmi. This User Agreement explains the rules that apply when you access or use the Tolmi
        application and its related services.
      </p>

      <p>
        By creating an account or using Tolmi, you agree to this User Agreement. Tolmi is available in supported
        countries and regions worldwide, excluding mainland China.
      </p>

      <h2>1. Account and Eligibility</h2>
      <p>
        You must provide accurate information when creating an account and keep your login information secure.
      </p>
      <p>
        You are responsible for all activity conducted through your account. You must be legally permitted to use Tolmi
        under the laws of your country or region. Where required, minors must obtain permission from a parent or legal
        guardian.
      </p>

      <h2>2. User Content</h2>
      <p>
        Tolmi allows users to create, upload, publish, and share videos, captions, comments, profile information, and
        other content.
      </p>
      <p>
        You retain ownership of the content you create. By publishing content on Tolmi, you grant Tolmi a
        non-exclusive, worldwide, royalty-free license to host, store, display, process, and distribute that content only
        as necessary to operate, improve, and promote the service.
      </p>
      <p>
        You must only publish content that you own or have permission to use.
      </p>

      <h2>3. Prohibited Content and Conduct</h2>
      <p>
        You must not use Tolmi to publish, share, promote, or engage in:
      </p>
      <ul>
        <li>Illegal, fraudulent, misleading, or harmful activities.</li>
        <li>Harassment, bullying, threats, personal attacks, insults, or abusive language toward other users.</li>
        <li>Hateful, discriminatory, sexually explicit, excessively violent, or otherwise offensive content.</li>
        <li>Content that exploits, harms, or endangers minors.</li>
        <li>Content that infringes copyrights, trademarks, privacy rights, or other legal rights.</li>
        <li>Spam, scams, impersonation, unauthorized advertising, or malicious links.</li>
        <li>
          Attempts to disrupt, damage, reverse engineer, or gain unauthorized access to Tolmi or another user's account.
        </li>
      </ul>
      <p>
        Users must communicate respectfully. Disagreements do not permit abusive, humiliating, threatening, or insulting
        behavior.
      </p>

      <h2>4. Content Review and Enforcement</h2>
      <p>
        Tolmi may review, restrict, hide, or remove content that violates this User Agreement, applicable laws, or our
        community rules.
      </p>
      <p>
        We may warn, restrict, suspend, or permanently terminate accounts involved in serious or repeated violations. In
        urgent situations, we may take action without prior notice to protect users or the service.
      </p>
      <p>
        Tolmi does not guarantee that all inappropriate content will be identified immediately.
      </p>

      <h2>5. Reporting and Blocking</h2>
      <p>
        Users may report content or accounts they believe violate these rules. Tolmi will review reports and may take
        appropriate action.
      </p>
      <p>
        Users may also block other accounts to limit unwanted interactions. Misuse of the reporting system, including
        knowingly submitting false reports, is prohibited.
      </p>

      <h2>6. Privacy</h2>
      <p>
        Your use of Tolmi is also subject to the Tolmi Privacy Policy. You should review the Privacy Policy to
        understand how personal information is collected, used, stored, and protected.
      </p>
      <p>
        You are responsible for deciding which information and content you make publicly visible on your profile.
      </p>

      <h2>7. Service Availability</h2>
      <p>
        Tolmi may update, modify, suspend, or discontinue features when necessary. We do not guarantee that the service
        will always be available, uninterrupted, or error-free.
      </p>
      <p>
        Tolmi is provided on an "as available" basis to the extent permitted by applicable law.
      </p>

      <h2>8. Account Termination</h2>
      <p>
        You may stop using Tolmi at any time.
      </p>
      <p>
        Tolmi may restrict or terminate access when a user violates this User Agreement, creates risks for other users,
        misuses the service, or when required by law.
      </p>
      <p>
        Termination does not remove responsibilities arising from conduct that occurred before the account was
        terminated.
      </p>

      <h2>9. Changes to This Agreement</h2>
      <p>
        We may update this User Agreement to reflect changes to Tolmi, legal requirements, or safety practices.
      </p>
      <p>
        When material changes are made, we may provide notice within the app. Continued use of Tolmi after the updated
        agreement becomes effective means you accept the revised terms.
      </p>

      <h2>10. Contact Us</h2>
      <p>
        For questions, reports, or concerns regarding this User Agreement, contact:
      </p>
      <p>
        <strong>Email: <a href="mailto:tolmi@gmail.com">tolmi@gmail.com</a></strong>
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'TolmiUserAgreement'
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
  margin: 0 0 8px;
}

a {
  color: inherit;
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
