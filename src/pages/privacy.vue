<template>
  <div class="meana-privacy-policy-page">
    <main>
      <div class="hero">
        <span class="eyebrow">Privacy by design</span>
        <h1>Meana Privacy Policy</h1>
        <p class="date">Effective date: July 8, 2026</p>
      </div>

      <div class="summary">
        Meana is designed for slow, respectful communication. We collect only the information needed to create your account, show your profile, operate safety features, and keep the service reliable.
      </div>

      <section>
        <h2>1. Information we collect</h2>
        <p>We may collect account information such as your email address, display name, age confirmation, approximate location, profile details, photos or videos you choose to upload, topic answers, likes, reports, and safety-related settings.</p>
        <p>We do not require you to publish exact addresses, phone numbers, government ID numbers, or external contact details on your public profile.</p>
      </section>

      <section>
        <h2>2. How we use information</h2>
        <ul>
          <li>Create and protect your Meana account.</li>
          <li>Show your profile, topic posts, video moments, and public replies inside the app.</li>
          <li>Support matching, conversation safety, trust progress, and moderation workflows.</li>
          <li>Detect misuse, spam, harmful content, and rule violations.</li>
          <li>Maintain, improve, and troubleshoot app performance.</li>
        </ul>
      </section>

      <section>
        <h2>3. Profile and public content</h2>
        <p>Profile photos, display names, approximate location, bio, tags, topic answers, and video captions may be visible to other members depending on where you post them. Your email address is used for login and is not shown as a public profile field.</p>
      </section>

      <section>
        <h2>4. Location privacy</h2>
        <p>Meana is built around approximate location. We use city-area or region-level hints to support relevance and safety. Do not share exact addresses in profile text, videos, topics, or conversations.</p>
      </section>

      <section>
        <h2>5. Photos, videos, and camera access</h2>
        <p>If you choose to upload a photo or video, the app may request access to your camera or photo library. You can deny or change these permissions in iOS Settings. Uploaded media should respect other people’s privacy and must not include harmful, misleading, or non-consensual content.</p>
      </section>

      <section>
        <h2>6. Safety, moderation, and reports</h2>
        <p>Reports, blocks, content reviews, trust progress, and related safety signals may be used to enforce community rules, prevent harm, and protect members. We may restrict accounts or remove content when necessary.</p>
      </section>

      <section>
        <h2>7. Sharing and service providers</h2>
        <p>We do not sell your personal information. We may share limited information with service providers that help operate hosting, analytics, security, customer support, crash reporting, or payment features, subject to appropriate confidentiality and security obligations.</p>
      </section>

      <section>
        <h2>8. Data retention</h2>
        <p>We keep account and activity information for as long as needed to provide Meana, meet legal obligations, resolve disputes, and enforce safety rules. Deleted content may remain in backups for a limited period or be retained when required for safety, legal, or abuse-prevention reasons.</p>
      </section>

      <section>
        <h2>9. Your choices</h2>
        <ul>
          <li>You can edit profile fields and remove content you control.</li>
          <li>You can manage camera and photo permissions in iOS Settings.</li>
          <li>You can stop using Meana at any time.</li>
          <li>You may request account assistance or deletion through Meana support.</li>
        </ul>
      </section>

      <section>
        <h2>10. Children and age requirements</h2>
        <p>Meana is intended for adults only. You must be 18 or older to create an account. If we learn that an underage person has created an account, we may remove the account and associated content.</p>
      </section>

      <section>
        <h2>11. Contact</h2>
        <p>For privacy questions, account requests, or safety concerns, contact Meana support at support@meana.app.</p>
      </section>

      <p class="footer">This policy may be updated as Meana evolves. Continued use after an update means the updated policy applies.</p>
    </main>
  </div>
</template>

<style scoped>
.meana-privacy-policy-page {
  color-scheme: light;
  --bg: #fcf8f1;
  --card: #ffffff;
  --ink: #28282b;
  --brown: #3b2017;
  --muted: #707076;
  --coral: #f5686a;
  --line: #e9e1d7;
  --soft: #f6efe3;
  --green: #4e8765;
  min-height: 100vh;
  margin: 0;
  padding: 16.5px 15px 31.5px;
  background: var(--bg);
  color: var(--ink);
  font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Helvetica Neue", Arial, sans-serif;
}

.meana-privacy-policy-page,
.meana-privacy-policy-page * {
  box-sizing: border-box;
}

.hero {
  padding: 6px 0 16.5px;
}

.eyebrow {
  display: inline-flex;
  align-items: center;
  min-height: 24px;
  padding: 0 10.5px;
  border-radius: 999px;
  background: #e8f1e8;
  color: var(--green);
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
  border: 1px solid var(--line);
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

.footer {
  margin: 15px 0 0;
  color: var(--muted);
  font-size: 9.75px;
  line-height: 1.5;
  text-align: center;
}
</style>
