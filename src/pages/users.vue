<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Barb User Agreement</h1>

      <p class="effective-date"><strong>Effective Date: July 1, 2026</strong></p>

      <p>
        Welcome to Barb. This User Agreement ("Agreement") outlines the terms, rules, and conditions that apply when you access or use Barb,
        including our mobile application, AI-assisted reply tools, account features, messages, user interactions, and related services.
      </p>

      <p>
        By creating an account, signing in, accessing Barb, sending messages, or otherwise using Barb, you agree to bound by this Agreement.
        If you do not agree, please do not use Barb.
      </p>

      <h2>1. Eligibility and Account Security</h2>
      <p>
        You must be old enough to legally form a binding contract and use online services in your jurisdiction. 
        You agree to provide accurate, up-to-date registration information and maintain the security of your login credentials. 
        You are solely responsible for all activity that occurs under your account.
      </p>

      <h2>2. User Generated Content (UGC) Safety and Prohibited Conduct (Apple Guideline 1.2 Compliance)</h2>
      <p>
        Because Barb supports private one-on-one chats and group conversations, it involves User Generated Content (UGC). 
        In strict compliance with <strong>Apple App Store Review Guideline 1.2</strong>, we enforce a <strong>Zero-Tolerance Policy</strong> 
        towards objectionable, abusive, or harmful content and behaviors.
      </p>
      
      <h3>A. Strictly Prohibited Content</h3>
      <p>You agree not to generate, send, transmit, or share any content that:</p>
      <ul>
        <li>Is obscene, pornographic, sexually explicit, or contains adult themes;</li>
        <li>Is defamatory, libelous, harassing, abusive, threatening, or constitutes cyber-bullying or stalking;</li>
        <li>Promotes hate speech, racism, bigotry, discrimination, or violence against any individual or group;</li>
        <li>Encourages illegal acts, financial fraud, scams, gambling, or self-harm;</li>
        <li>Infringes on third-party copyrights, trademarks, privacy rights, or other proprietary rights.</li>
      </ul>

      <h3>B. Built-in Safety Controls and Moderation Mechanisms</h3>
      <p>To ensure a clean, comfortable, and trusted communication space, Barb provides and strictly implements the following features:</p>
      <ul>
        <li><strong>Filtering:</strong> We implement automated keyword and content filtering systems to capture and flag offensive text patterns.</li>
        <li><strong>Block Mechanism (One-Click Block):</strong> Users can instantly block any contact at any time. Once blocked, the target user is completely restricted from sending you any further messages.</li>
        <li><strong>Report Mechanism (One-Click Report):</strong> Users can report objectionable content or abusive behaviors directly inside any chat or conversation.</li>
        <li><strong>24-Hour Review Commitment:</strong> Our dedicated moderation team reviews all submitted user reports within 24 hours of submission.</li>
      </ul>

      <h3>C. Enforcement and Account Penalties</h3>
      <p>
        If a user is found violating this Agreement or engaging in harassment, we reserve the right, at our sole discretion and without prior notice, 
        to remove the objectionable content, restrict account privileges, or <strong>immediately and permanently terminate or ban the offending user's account</strong>.
      </p>

      <h2>3. AI Quick Reply Disclaimer</h2>
      <p>
        Barb offers AI Quick Reply functionalities powered by algorithmic language models to provide contextual text suggestions in multiple tones. 
        <strong>You acknowledge and agree that AI-generated suggestions are for your reference only. You retain full review obligations, ownership, and sole 
        legal responsibility for any text message that you actively choose to send.</strong> Barb is not liable for any misunderstandings, disputes, or legal consequences 
        resulting from messages sent using AI assistance.
      </p>

      <h2>4. Intellectual Property</h2>
      <p>
        All rights, titles, and interests in Barb, including our user interfaces, design assets, logos, application code, and proprietary AI implementation mechanics, 
        belong exclusively to us. You retain ownership of the original text content you compose, but you grant Barb the necessary technical licenses to host, process, 
        and display your messages locally and securely on your communication endpoints.
      </p>

      <h2>5. Disclaimers and Limitation of Liability</h2>
      <p>
        Barb is provided on an "as is" and "as available" basis without warranties of any kind. To the maximum extent permitted by applicable law, Barb and its operators 
        shall not be liable for any indirect, incidental, special, consequential, or punitive damages, or any loss of data, profits, or goodwill arising from your use of the application.
      </p>

      <h2>6. Termination</h2>
      <p>
        You may stop using Barb and delete your account at any time. We may suspend or terminate your access to Barb immediately if you violate any portion of this Agreement, 
        fail to respect other users' privacy, or pose a legal or security risk to the Barb community.
      </p>

      <h2>7. Contact Us</h2>
      <p>
        If you have questions, feedback, or need to report an urgent safety vulnerability regarding this User Agreement, please contact us at:
        <br />
        <strong>Email: barb@gmail.com</strong>
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'BarbUserAgreement'
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