<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Tinkie User Agreement</h1>

      <p class="effective-date"><strong>Effective Date: July 17, 2026</strong></p>

      <p>
        Welcome to Tinkie – Voice Songs ("Tinkie", "we", "our", or "us"). This User Agreement explains the rules
        for using Tinkie, a music guessing and voice-based entertainment app built around song cues, rhythm rounds,
        singing clues, quick answers, profile moments, and relaxed audio interaction.
      </p>

      <p>
        By creating an account, signing in, joining a song activity, posting a moment, using profile features,
        or otherwise accessing Tinkie, you agree to this User Agreement and our Privacy Policy. If you do not agree,
        do not use Tinkie.
      </p>

      <h2>1. Eligibility</h2>
      <p>
        You must be old enough to legally use interactive online services in your country or region and must have
        the legal capacity to accept this agreement. If a feature requires additional age, identity, or local-law
        eligibility checks, you agree to provide accurate information.
      </p>

      <h2>2. Account Registration and Security</h2>
      <p>
        You may need an account to use profile, event, room, posting, following, reporting, or other user-specific
        features. You agree to provide accurate registration information, keep your login credentials secure,
        and accept responsibility for activity under your account.
      </p>

      <h2>3. Tinkie Music Experience</h2>
      <p>
        Tinkie is for entertainment, music discovery, song guessing, singing clues, rhythm-based challenges,
        and friendly audio interaction. You may not use Tinkie as an emergency service, professional advice tool,
        rights-clearance platform, or substitute for obtaining music permissions where required.
      </p>

      <h2>4. User Content</h2>
      <p>
        You may create or submit profile information, room activity, song guesses, singing clues, captions,
        reactions, reports, and other content. You keep ownership of content you own, but you grant Tinkie
        a non-exclusive, worldwide, royalty-free license to host, store, display, adapt for technical purposes,
        moderate, and use that content as needed to operate and protect the app.
      </p>

      <h2>5. Music and Intellectual Property</h2>
      <p>
        You are responsible for the content you provide. Do not upload, perform, copy, or distribute music,
        artwork, images, names, recordings, or other materials unless you have the right to do so or your use
        is otherwise legally permitted. Tinkie may remove content that appears to infringe rights or violate policy.
      </p>

      <h2>6. Prohibited Conduct</h2>
      <p>
        You agree not to post or promote content involving child harm, sexual exploitation, pornography,
        harassment, bullying, threats, hate, discrimination, violence, self-harm encouragement, fraud, impersonation,
        spam, malware, illegal activity, or harmful claims about recent or current events.
      </p>

      <p>
        You also agree not to disrupt song rounds, abuse reporting tools, evade restrictions, scrape data,
        reverse engineer the app, interfere with security, misrepresent your identity, or use Tinkie to pressure,
        exploit, or endanger other users.
      </p>

      <h2>7. Safety Tools, Reports, and Blocking</h2>
      <p>
        Tinkie may provide tools to report content, report users, block users, filter objectionable material,
        and review activity. We may remove content, limit visibility, suspend accounts, terminate access,
        or take other action when we believe this agreement, law, safety rules, or App Store requirements have
        been violated.
      </p>

      <h2>8. Account Restrictions and Termination</h2>
      <p>
        We may restrict, suspend, or terminate your access if your activity creates risk, violates this agreement,
        harms users, infringes rights, or interferes with Tinkie. Serious or repeated violations may result in
        permanent account removal and loss of access to local or account-based features.
      </p>

      <h2>9. Privacy</h2>
      <p>
        Our Privacy Policy explains how Tinkie handles information, including account details, profile information,
        local device storage, safety reports, technical data, and permission-based features such as microphone,
        camera, or photos.
      </p>

      <h2>10. App Permissions</h2>
      <p>
        Some features may request access to microphone, camera, photos, or notifications. You may deny or revoke
        permissions through device settings. Tinkie will not require unrelated permissions for core access, but
        features depending on a denied permission may not work.
      </p>

      <h2>11. Availability and Changes</h2>
      <p>
        Tinkie may change, pause, remove, or update features at any time. We may also update this agreement.
        The updated version will apply when made available in the app or through another reasonable method.
      </p>

      <h2>12. Disclaimers</h2>
      <p>
        Tinkie is provided on an "as is" and "as available" basis. We do not guarantee that every song clue,
        activity, profile, moment, or feature will be uninterrupted, accurate, secure, available, or error-free.
      </p>

      <h2>13. Limitation of Liability</h2>
      <p>
        To the maximum extent permitted by law, Tinkie and its operators will not be liable for indirect,
        incidental, special, consequential, exemplary, or punitive damages, or for lost data, content, goodwill,
        or opportunities arising from your use of the app.
      </p>

      <h2>14. Governing Requirements</h2>
      <p>
        You are responsible for following all laws that apply to your use of Tinkie. If any part of this agreement
        is found unenforceable, the remaining parts remain in effect to the fullest extent permitted by law.
      </p>

      <h2>15. Contact</h2>
      <p>
        If you have questions about this User Agreement, safety issues, account concerns, reports, or rights requests,
        contact us at tinkie@gmail.com.
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'TinkieUserAgreement'
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
