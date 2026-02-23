<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ihsan - Support</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background: #0F172A;
      color: rgba(255,255,255,0.85);
      line-height: 1.7;
      -webkit-font-smoothing: antialiased;
    }
    .container {
      max-width: 720px;
      margin: 0 auto;
      padding: 60px 24px 80px;
    }
    .hero {
      text-align: center;
      margin-bottom: 56px;
    }
    .hero h1 {
      font-size: 42px;
      font-weight: 300;
      letter-spacing: 6px;
      text-transform: uppercase;
      color: #fff;
      margin-bottom: 8px;
    }
    .hero p {
      font-size: 15px;
      color: rgba(255,255,255,0.4);
      letter-spacing: 0.5px;
    }
    .nav {
      display: flex;
      gap: 12px;
      justify-content: center;
      margin-bottom: 48px;
      flex-wrap: wrap;
    }
    .nav a {
      padding: 10px 24px;
      border-radius: 100px;
      font-size: 14px;
      font-weight: 600;
      text-decoration: none;
      color: rgba(255,255,255,0.6);
      background: rgba(255,255,255,0.06);
      border: 1px solid rgba(255,255,255,0.08);
      transition: all 0.2s;
    }
    .nav a:hover, .nav a.active {
      color: #fff;
      background: rgba(14,165,233,0.15);
      border-color: rgba(14,165,233,0.3);
    }
    .section { display: none; }
    .section.active { display: block; }
    h2 {
      font-size: 24px;
      font-weight: 700;
      color: #fff;
      margin-bottom: 24px;
      padding-bottom: 12px;
      border-bottom: 1px solid rgba(255,255,255,0.06);
    }
    h3 {
      font-size: 17px;
      font-weight: 600;
      color: #fff;
      margin-top: 32px;
      margin-bottom: 8px;
    }
    p, li {
      font-size: 15px;
      color: rgba(255,255,255,0.6);
      margin-bottom: 12px;
    }
    ul {
      padding-left: 20px;
      margin-bottom: 12px;
    }
    li { margin-bottom: 6px; }
    .support-card {
      background: rgba(255,255,255,0.04);
      border: 1px solid rgba(255,255,255,0.06);
      border-radius: 16px;
      padding: 28px;
      margin-bottom: 20px;
    }
    .support-card h3 {
      margin-top: 0;
      margin-bottom: 12px;
    }
    a.email-link {
      color: #0EA5E9;
      text-decoration: none;
    }
    a.email-link:hover { text-decoration: underline; }
    .updated {
      font-size: 13px;
      color: rgba(255,255,255,0.3);
      margin-bottom: 32px;
    }
    .footer {
      text-align: center;
      margin-top: 64px;
      padding-top: 24px;
      border-top: 1px solid rgba(255,255,255,0.06);
      font-size: 13px;
      color: rgba(255,255,255,0.25);
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="hero">
      <h1>Ihsan</h1>
      <p>Your path to recovery, guided by faith</p>
    </div>

    <div class="nav">
      <a href="#support" class="active" onclick="show('support')">Support</a>
      <a href="#privacy" onclick="show('privacy')">Privacy Policy</a>
      <a href="#terms" onclick="show('terms')">Terms of Service</a>
    </div>

    <!-- Support -->
    <div id="support" class="section active">
      <h2>Support</h2>

      <div class="support-card">
        <h3>Contact Us</h3>
        <p>For any questions, issues, or feedback, reach out to us at:</p>
        <p><a class="email-link" href="mailto:support@ihsanapp.com">support@ihsanapp.com</a></p>
        <p>We aim to respond within 48 hours.</p>
      </div>

      <div class="support-card">
        <h3>Manage Your Subscription</h3>
        <p>Subscriptions are managed through the App Store. To cancel or change your plan:</p>
        <ul>
          <li>Open <strong>Settings</strong> on your iPhone</li>
          <li>Tap your name at the top</li>
          <li>Tap <strong>Subscriptions</strong></li>
          <li>Select <strong>Ihsan</strong> and choose your option</li>
        </ul>
      </div>

      <div class="support-card">
        <h3>Delete Your Data</h3>
        <p>All your data is stored locally on your device. To delete all data, simply delete the Ihsan app from your device. No data is stored on external servers, so deletion is immediate and permanent.</p>
      </div>

      <div class="support-card">
        <h3>Crisis Resources</h3>
        <p>Ihsan is not a substitute for professional help. If you are experiencing a mental health crisis, please contact:</p>
        <ul>
          <li><strong>988 Suicide & Crisis Lifeline</strong> &mdash; Call or text 988 (US)</li>
          <li><strong>Crisis Text Line</strong> &mdash; Text HOME to 741741</li>
          <li>Your local emergency services</li>
        </ul>
      </div>
    </div>

    <!-- Privacy Policy -->
    <div id="privacy" class="section">
      <h2>Privacy Policy</h2>
      <p class="updated">Last updated: February 2025</p>

      <p>Ihsan ("we", "our", "the app") is committed to protecting your privacy. This Privacy Policy explains how we handle your information when you use our mobile application.</p>

      <h3>Information We Store</h3>
      <p>Ihsan stores the following information locally on your device only:</p>
      <ul>
        <li>Your recovery streak and progress data</li>
        <li>Journal entries and personal reflections</li>
        <li>Workout logs and exercise data</li>
        <li>App preferences (language, notification settings)</li>
      </ul>

      <h3>Data Storage &amp; Security</h3>
      <p>All your personal data is stored exclusively on your device using local storage. We do not transmit, upload, or store your data on any external servers. Your recovery journey, journal entries, and personal information never leave your device. If you delete the app, all data is permanently removed.</p>

      <h3>No Data Sharing</h3>
      <p>We do not sell, trade, rent, or share your personal information with any third parties. Since all data remains on your device, there is no data to share.</p>

      <h3>Analytics &amp; Tracking</h3>
      <p>Ihsan does not use any third-party analytics, tracking, or advertising services. We do not collect usage statistics, behavioral data, or device identifiers.</p>

      <h3>Subscription &amp; Payments</h3>
      <p>Subscription purchases are processed entirely through Apple's App Store. We do not have access to your payment information, credit card details, or Apple ID. All billing is managed by Apple according to their privacy policy.</p>

      <h3>Changes to This Policy</h3>
      <p>We may update this Privacy Policy from time to time. Any changes will be reflected in the app with an updated revision date.</p>

      <h3>Contact Us</h3>
      <p>If you have questions about this Privacy Policy, please contact us at <a class="email-link" href="mailto:support@ihsanapp.com">support@ihsanapp.com</a>.</p>
    </div>

    <!-- Terms of Service -->
    <div id="terms" class="section">
      <h2>Terms of Service</h2>
      <p class="updated">Last updated: February 2025</p>

      <p>These Terms of Service ("Terms") govern your use of the Ihsan mobile application. By using Ihsan, you agree to these Terms.</p>

      <h3>Acceptance of Terms</h3>
      <p>By downloading, installing, or using Ihsan, you agree to be bound by these Terms. If you do not agree, please do not use the app.</p>

      <h3>Description of Service</h3>
      <p>Ihsan is a self-improvement and recovery support application that provides tools including streak tracking, crisis intervention techniques, educational content, journaling, workout tracking, and Islamic spiritual guidance. Ihsan is not a medical or therapeutic service and does not replace professional help.</p>

      <h3>Subscriptions &amp; Billing</h3>
      <p>Ihsan offers a premium subscription with the following terms:</p>
      <ul>
        <li>Payment is charged to your Apple ID account at confirmation of purchase.</li>
        <li>Subscription automatically renews unless cancelled at least 24 hours before the end of the current billing period.</li>
        <li>Your account will be charged for renewal within 24 hours prior to the end of the current period at the subscription rate.</li>
        <li>You can manage and cancel subscriptions in your Apple ID account settings.</li>
      </ul>

      <h3>Free Access Program</h3>
      <p>Users who cannot afford the subscription may access Ihsan for free by affirming a sworn oath. This access is provided in good faith and is intended for those with genuine financial hardship. We reserve the right to modify or discontinue the free access program at any time.</p>

      <h3>Health Disclaimer</h3>
      <p>Ihsan is a self-help support tool and is not a substitute for professional medical advice, diagnosis, or treatment. If you are experiencing a mental health crisis, please contact a qualified healthcare provider or emergency services. The breathing exercises, grounding techniques, and other tools provided are for general wellness support only.</p>

      <h3>Limitation of Liability</h3>
      <p>Ihsan is provided "as is" without warranties of any kind. We are not liable for any damages arising from your use of the app. Your use of Ihsan is at your own risk. In no event shall our total liability to you exceed the amount you have actually paid to us in the twelve (12) months preceding the claim.</p>

      <h3>Intellectual Property</h3>
      <p>All content within Ihsan, including text, graphics, and design, is the property of Ihsan or its content suppliers. Quranic verses, hadith, and Islamic scholarly quotes are attributed to their original sources and are used for educational purposes.</p>

      <h3>Termination</h3>
      <p>We reserve the right to terminate or suspend access to Ihsan at any time, without notice, for conduct that we believe violates these Terms or is harmful to other users or the app.</p>

      <h3>Changes to Terms</h3>
      <p>We may revise these Terms at any time. Continued use of Ihsan after changes constitutes acceptance of the new Terms.</p>

      <h3>Language</h3>
      <p>These Terms of Service may be translated for convenience. In the event of any conflict or inconsistency between the English version and any translation, the English version shall prevail.</p>

      <h3>Contact Us</h3>
      <p>If you have questions about these Terms, please contact us at <a class="email-link" href="mailto:support@ihsanapp.com">support@ihsanapp.com</a>.</p>
    </div>

    <div class="footer">
      &copy; 2025 Ihsan. All rights reserved.
    </div>
  </div>

  <script>
    function show(id) {
      document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
      document.querySelectorAll('.nav a').forEach(a => a.classList.remove('active'));
      document.getElementById(id).classList.add('active');
      document.querySelector('.nav a[href="#' + id + '"]').classList.add('active');
    }
    if (window.location.hash) {
      var id = window.location.hash.substring(1);
      if (document.getElementById(id)) show(id);
    }
  </script>
</body>
</html>
