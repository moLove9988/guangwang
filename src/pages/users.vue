<template>
  <div class="agreement-page">
    <section class="agreement-section">
      <h1>Pacel 利用規約</h1>
      <p class="effective-date"><strong>制定日：2026年7月21日</strong></p>
      <p>本利用規約（以下「本規約」）は、Pacel（以下「本サービス」）の利用条件を定めるものです。利用者は、本サービスを利用することにより、本規約およびプライバシーポリシーに同意したものとします。</p>

      <section class="support-notice">
        <h2>Pacel サポート窓口</h2>
        <p>本サービスに関するご質問、不具合のご報告、ご意見および機能改善のご要望は、<a href="mailto:support@pacel.com">support@pacel.com</a> までお問い合わせください。</p>
      </section>

      <h2>1. 利用資格</h2>
      <p>利用者は、適用される法令を遵守し、自らの責任で本サービスを利用するものとします。未成年の方は、必要に応じて保護者の同意を得たうえで利用してください。</p>

      <h2>2. アカウント</h2>
      <p>利用者は、登録情報を正確かつ最新の状態に保つものとし、アカウントを第三者に利用させないものとします。</p>

      <h2>3. コミュニティ機能</h2>
      <p>本サービスは、学生同士の交流およびキャンパスに関する情報共有を目的としています。利用者は、他の利用者の権利および安全に配慮して利用するものとします。</p>

      <h2>4. 利用者の投稿内容</h2>
      <p>利用者は、投稿、画像、コメント、メッセージその他の内容について、必要な権利および許可を有していることを保証します。利用者は、自らが公開または送信した内容について責任を負います。</p>

      <h2>5. 禁止事項</h2>
      <p>利用者は、法令または公序良俗に反する行為、他者への嫌がらせ・差別・脅迫・なりすまし、個人情報の無断公開、著作権等の権利侵害、虚偽または詐欺的な情報の掲載、無断撮影・無断投稿、危険物や違法な物品の取引、不正なアクセス、通報機能の不正利用その他本サービスの安全な運営を妨げる行為をしてはなりません。</p>

      <h2>6. 通報、ブロックおよび対応</h2>
      <p>当社は、本規約に違反するおそれのある内容または利用行為について、必要な対応を行うことがあります。</p>

      <h2>7. コインおよびアプリ内課金</h2>
      <p>コインは本サービス内でのみ利用でき、現金その他の価値への換金、譲渡または本サービス外での利用はできません。購入の決済および返金の取扱いは、Appleの規約および適用法令に従います。</p>

      <h2>8. 失くし物・忘れ物および校内シェア</h2>
      <p>利用者間の連絡、物品の受け渡しおよびこれらに関連する判断は、利用者自身の責任で安全に行ってください。当社は、利用者間で生じた紛争または損害について責任を負いません。</p>

      <h2>9. サービスの変更・停止</h2>
      <p>当社は、必要に応じて本サービスの内容を変更、追加、中断または終了することがあります。法令で認められる範囲で、本サービスの利用により生じた間接的または結果的な損害について責任を負いません。</p>

      <h2>10. アカウント削除</h2>
      <p>利用者は、アプリ内の設定からアカウント削除を開始できます。削除に関するご質問は、Pacel サポート窓口までご連絡ください。</p>

      <h2>11. 規約の変更</h2>
      <p>当社は、法令や本サービスの内容の変更に応じて本規約を変更することがあります。変更後の規約は、本ページまたは本サービス内で公表した時点から適用されます。</p>

      <h2>12. お問い合わせ</h2>
      <p>Pacel サポート窓口：<a href="mailto:support@pacel.com">support@pacel.com</a></p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'PacelUserAgreement'
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

.support-notice {
  margin: 24px 0 28px;
  padding: 18px;
  border: 1px solid #d9dce3;
  border-radius: 12px;
  background: #f8f9fb;
}

.support-notice h2 {
  margin-top: 0;
}

.support-notice p {
  margin-bottom: 0;
}

@media screen and (max-width: 600px) {
  .agreement-page { padding: 20px 16px; }
  h1 { font-size: 24px; }
  h2 { font-size: 17px; }
  p { font-size: 14px; }
}
</style>
