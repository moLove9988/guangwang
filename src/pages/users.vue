<template>
  <div class="meana-user-agreement-page">
    <main>
      <div class="hero">
        <span class="eyebrow">Respectful use</span>
        <h1>Meana User Agreement</h1>
        <p class="date">Effective date: July 8, 2026</p>
      </div>

      <div class="summary">
        These terms govern your use of Meana. By creating an account or using the app, you agree to use Meana honestly, lawfully, and respectfully.
      </div>

      <section>
        <h2>1. Eligibility</h2>
        <p>You must be at least 18 years old to use Meana. You agree to provide accurate account information and to keep your account secure. You are responsible for activity that occurs through your account.</p>
      </section>

      <section>
        <h2>2. Community standards</h2>
        <p>Meana is designed for mature, slow, and respectful conversations. You agree not to:</p>
        <ul>
          <li>Harass, threaten, shame, pressure, or impersonate another person.</li>
          <li>Request money, financial assistance, gifts, investments, or payments from other members.</li>
          <li>Share illegal, hateful, sexual, exploitative, violent, or non-consensual content.</li>
          <li>Use Meana for spam, scams, fraud, commercial solicitation, or automated activity.</li>
          <li>Bypass safety rules, moderation tools, account restrictions, or trust protections.</li>
        </ul>
      </section>

      <section>
        <h2>3. Profiles, topics, and videos</h2>
        <p>You are responsible for the content you post, including profile details, photos, videos, topic questions, answers, captions, and replies. Do not post content that violates another person’s rights or privacy.</p>
        <p>Meana may remove content, limit visibility, or restrict accounts when content appears unsafe, misleading, illegal, or inconsistent with these terms.</p>
      </section>

      <section>
        <h2>4. Safety and private contact</h2>
        <p>Do not pressure another member to share phone numbers, addresses, social accounts, payment details, or other external contact information. If you choose to meet someone outside the app, use public places, tell someone you trust, and make decisions at your own pace.</p>
      </section>

      <section>
        <h2>5. Purchases and coins</h2>
        <p>If Meana offers coins, subscriptions, boosts, or other paid features, purchases are handled through the applicable app store or payment provider. Digital items may be limited to your account and may not be transferable, refundable, or redeemable for cash except where required by law.</p>
      </section>

      <section>
        <h2>6. Reports, moderation, and enforcement</h2>
        <p>We may review reports, remove content, suspend features, disable accounts, or take other safety actions when needed. We are not required to publish moderation details, but we aim to apply safety decisions consistently and responsibly.</p>
      </section>

      <section>
        <h2>7. Intellectual property</h2>
        <p>You keep ownership of content you create, but you grant Meana a non-exclusive license to host, display, process, and distribute that content as needed to operate the app. Meana owns the app design, software, trademarks, and service materials.</p>
      </section>

      <section>
        <h2>8. Service availability</h2>
        <p>Meana may change, pause, or discontinue features from time to time. We work to keep the service reliable, but we do not guarantee uninterrupted access, specific matches, responses, visibility, or outcomes.</p>
      </section>

      <section>
        <h2>9. Account termination</h2>
        <p>You may stop using Meana at any time. We may suspend or terminate accounts that violate these terms, create safety risk, misuse the service, or are required to be restricted by law.</p>
      </section>

      <section>
        <h2>10. Disclaimers and responsibility</h2>
        <p>Meana provides tools for communication and safety reminders, but members are responsible for their own decisions and interactions. Use good judgment, protect your privacy, and report behavior that feels unsafe.</p>
      </section>

      <section>
        <h2>11. Changes to these terms</h2>
        <p>We may update this agreement as Meana evolves. If changes are material, we may provide notice in the app. Continued use after an update means you accept the updated agreement.</p>
      </section>

      <section>
        <h2>12. Contact</h2>
        <p>For account, safety, or agreement questions, contact Meana support at support@meana.app.</p>
      </section>

      <p class="footer">Thank you for helping keep Meana calm, honest, and safe.</p>
    </main>
  </div>
</template>

<style scoped>
.meana-user-agreement-page {
  color-scheme: light;
  --bg: #fcf8f1;
  --card: #ffffff;
  --ink: #28282b;
  --brown: #3b2017;
  --muted: #707076;
  --coral: #f5686a;
  --line: #e9e1d7;
  --soft: #fff1f1;
  --gold: #9a6715;
  min-height: 100vh;
  margin: 0;
  padding: 16.5px 15px 31.5px;
  background: var(--bg);
  color: var(--ink);
  font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Helvetica Neue", Arial, sans-serif;
}

.meana-user-agreement-page,
.meana-user-agreement-page * {
  box-sizing: border-box;
}

.hero { padding: 6px 0 16.5px; }

.eyebrow {
  display: inline-flex;
  align-items: center;
  min-height: 24px;
  padding: 0 10.5px;
  border-radius: 999px;
  background: #fff0d6;
  color: var(--gold);
  font-size: 9.75px;
  font-weight: 800;
  letter-spacing: 0;
}

h1 {
  margin: 13.5px 0 6px;
  color: var(--brown);
  font-size: 25.5px;
  line-height: 1.06;
  font-weight: 900;
  letter-spacing: 0;
}

.date {
  margin: 0;
  color: var(--muted);
  font-size: 10.5px;
  line-height: 1.45;
}

.summary {
  margin: 13.5px 0 16.5px;
  padding: 13.5px;
  border-radius: 18px;
  background: var(--soft);
  border: 1px solid #ffdede;
  color: var(--brown);
  font-size: 12px;
  line-height: 1.55;
  font-weight: 650;
}

section {
  margin: 10.5px 0;
  padding: 16.5px 13.5px;
  border-radius: 18px;
  background: var(--card);
  box-shadow: 0 10.5px 22.5px rgba(59, 32, 23, 0.06);
}

h2 {
  margin: 0 0 7.5px;
  color: var(--ink);
  font-size: 15px;
  line-height: 1.18;
  font-weight: 850;
  letter-spacing: 0;
}

p,
li {
  color: var(--muted);
  font-size: 11.25px;
  line-height: 1.58;
  letter-spacing: 0;
}

p { margin: 0 0 7.5px; }
p:last-child { margin-bottom: 0; }
ul { margin: 6px 0 0; padding-left: 14.25px; }
li { margin: 5.25px 0; }
strong { color: var(--ink); }

.footer {
  margin: 15px 0 0;
  color: var(--muted);
  font-size: 9.75px;
  line-height: 1.5;
  text-align: center;
}
</style>
