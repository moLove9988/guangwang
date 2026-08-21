<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Jessa Terms of Use</h1>

      <p class="effective-date"><strong>Effective Date: August 17, 2026</strong></p>

      <p>
        Welcome to Jessa. By creating an account, accessing, or using Jessa, you agree to these Terms of Use.
        If you do not agree, please do not use the App.
      </p>

      <h2>1. Eligibility</h2>
      <p>
        You must meet the minimum legal age required in your country or region to use Jessa. If you are under the age
        of legal majority, you must have permission from a parent or legal guardian.
      </p>
      <p>
        Jessa is available worldwide except in mainland China. You are responsible for ensuring that your use of Jessa
        complies with the laws applicable in your location.
      </p>

      <h2>2. Your Account</h2>
      <p>
        You are responsible for providing accurate information, protecting your login credentials, and all activity
        conducted through your account. You may not impersonate another person, create misleading accounts, sell or
        transfer your account, or use Jessa for unlawful purposes.
      </p>

      <h2>3. User Content</h2>
      <p>
        You may share live streams, voice or video content, photos, short clips, comments, messages, product listings,
        and other content through Jessa. You retain ownership of your content, but grant Jessa a worldwide,
        non-exclusive, royalty-free license to host, display, reproduce, and distribute it only as necessary to operate,
        promote, and improve the App.
      </p>
      <p>You must have all necessary rights and permissions before posting any content.</p>

      <h2>4. Prohibited Content and Conduct</h2>
      <p><strong>Jessa has zero tolerance for objectionable content and abusive users.</strong></p>
      <p>You must not post, stream, send, or promote content that:</p>
      <ul>
        <li>Is illegal, sexually explicit, pornographic, violent, threatening, hateful, discriminatory, fraudulent, or otherwise harmful;</li>
        <li>Exploits or endangers minors;</li>
        <li>Encourages self-harm, criminal activity, or dangerous behavior;</li>
        <li>Infringes copyrights, trademarks, privacy, publicity, or other rights;</li>
        <li>Reveals another person's private or sensitive information without permission;</li>
        <li>Contains scams, spam, malware, misleading promotions, or prohibited goods or services.</li>
      </ul>
      <p>
        You must not attack, insult, bully, harass, threaten, shame, stalk, discriminate against, or deliberately
        humiliate another user. Abusive language, repeated unwanted contact, malicious disruption of live rooms,
        and targeted personal attacks are strictly prohibited.
      </p>
      <p>
        Users may report inappropriate content and block abusive accounts. Jessa may review reports, remove content,
        restrict features, suspend or permanently terminate accounts, and cooperate with law enforcement where necessary.
      </p>

      <h2>5. Live and Communication Features</h2>
      <p>
        Use live rooms, voice calls, video calls, and messaging responsibly. Do not record, photograph, or distribute
        another person's communications without their permission where consent is legally required. Never share sensitive
        personal or financial information with unknown users.
      </p>

      <h2>6. Marketplace</h2>
      <p>
        Marketplace listings and transactions may be provided by independent users or third parties. Unless expressly
        stated otherwise, Jessa does not manufacture, own, endorse, or guarantee listed products. Buyers and sellers
        are responsible for product accuracy, legality, payment, delivery, returns, taxes, and compliance with applicable
        consumer laws.
      </p>

      <h2>7. Service Availability</h2>
      <p>
        We may update, modify, suspend, or discontinue any part of Jessa when reasonably necessary. We do not guarantee
        that the App will always be uninterrupted, secure, or error-free.
      </p>
      <p>
        To the extent permitted by law, Jessa is provided "as is" and we are not responsible for indirect losses,
        user conduct, user-generated content, third-party products, or interactions arranged through the App. Nothing
        in these Terms limits any consumer rights that cannot legally be excluded.
      </p>

      <h2>8. Termination</h2>
      <p>
        You may stop using Jessa at any time. We may restrict or terminate access if you violate these Terms, harm other
        users, create legal or security risks, or misuse the App.
      </p>

      <h2>9. Changes to These Terms</h2>
      <p>
        We may update these Terms to reflect changes to Jessa, applicable laws, or safety requirements. Updated Terms
        will be posted in the App with a revised effective date. Where required by law, we will provide additional
        notice or request your consent.
      </p>

      <h2>10. Contact Us</h2>
      <p>
        If you have questions, complaints, or wish to report content or conduct, contact us at:
        <a href="mailto:jessa@gmail.com">jessa@gmail.com</a>
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'JessaTermsOfUse'
}
</script>

<style scoped>
.agreement-page {
  box-sizing: border-box;
  width: 100%;
  min-height: 100vh;
  padding: 28px 18px 40px;
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
  margin: 0 0 18px;
  font-size: 28px;
  font-weight: 700;
  line-height: 1.3;
  color: #111111;
}

h2 {
  margin: 30px 0 12px;
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
  margin: 0 0 16px;
}

ul {
  margin: 0 0 18px 22px;
  padding: 0;
}

li {
  margin: 0 0 10px;
  padding-left: 2px;
}

a {
  color: #111111;
  text-decoration: underline;
  text-underline-offset: 3px;
}

.effective-date {
  margin-bottom: 22px;
  color: #111111;
}

@media screen and (max-width: 600px) {
  .agreement-page {
    padding: 22px 16px 34px;
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
