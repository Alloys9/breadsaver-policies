# Privacy Policy

**Last updated: July 21, 2026**

Eutopian Technologies ("we", "us", "our") operates the BreadSaver mobile application ("the App"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App. Please read it carefully.

By using BreadSaver, you consent to the practices described in this Privacy Policy.

---

## 1. Information We Collect

### 1.1 Information You Provide Directly

- **Account information**: email address and display name when you register
- **Financial data**: budget categories, transactions, accounts, savings goals, and scheduled transactions you manually enter into the App
- **Payment information**: subscription plan selections; actual payment processing is handled by Apple, Google Play, or Paystack (depending on platform) and we do not store your card details

### 1.2 Information Collected Automatically

- **Device and app information**: device type, operating system version, and app version, collected as part of crash and diagnostic reporting
- **Crash and diagnostic reports**: error logs, crash stack traces, and performance data collected via Firebase Crashlytics to help us diagnose and fix issues
- **Security and integrity signals**: Firebase App Check verifies that requests come from a genuine, unmodified copy of the App running on a genuine device (via Google Play Integrity on Android and Apple App Attest/DeviceCheck on iOS); this does not identify you personally
- **Audit and security logs**: administrative and security-relevant actions on your account (e.g. sign-in, 2FA changes, subscription changes) are logged internally for fraud prevention and support purposes

We do not use Firebase Analytics or any advertising/analytics SDK, and we do not collect advertising identifiers.

### 1.3 Information from Third Parties

- **Authentication providers**: if you sign in via Google or Apple, we receive basic profile information (name, email) from those providers
- **Payment processors**: depending on your platform, Apple, Google, or Paystack provide us with transaction confirmation data (plan purchased, transaction reference, subscription status) but never your full card or banking details

---

## 2. How We Use Your Information

We use the information we collect to:

- **Provide and operate the Service**: create and manage your account, process your subscription, and deliver the features you use
- **Secure your account**: support optional two-factor authentication (TOTP), verify your identity via one-time email codes during signup, and enforce step-up verification for sensitive actions
- **Personalize your experience**: display your financial data accurately and remember your preferences
- **Process payments**: verify subscription status and enforce plan limits
- **Send transactional communications**: subscription confirmations, renewal reminders, payment failure notifications, and account security alerts
- **Fix bugs and improve stability**: use crash and diagnostic reports to identify and resolve issues
- **Comply with legal obligations**: respond to lawful requests from public authorities and comply with applicable laws
- **Protect against fraud and abuse**: monitor for suspicious activity, maintain security audit logs, and enforce our Terms of Service

We do **not** use your data for:
- Selling to third-party advertisers
- Building advertising profiles
- Any automated decision-making that significantly affects you

---

## 3. How We Share Your Information

We do not sell your personal data. We may share your information only in the following circumstances:

### 3.1 Service Providers

We share data with trusted third-party vendors who help us operate the App:

| Provider | Purpose | Data Shared |
|----------|---------|-------------|
| **Google Firebase** | Authentication, database, cloud functions, crash reporting, app integrity verification | Account data, financial data you enter, crash logs |
| **Apple** | Payment processing (iOS, via StoreKit), app distribution | Email address, subscription plan, transaction reference |
| **Google Play** | Payment processing (Android, via Play Billing) | Email address, subscription plan, transaction reference |
| **Paystack** | Payment processing (web/desktop only, outside the App Store/Play Store apps) | Email address, subscription plan, transaction reference |
| **Resend** | Transactional email delivery | Email address, plan name |

Your subscription is billed through Apple or Google Play when you use the mobile App; Paystack is used only if you subscribe through our website. All service providers are contractually obligated to protect your data and use it only for the purposes we specify.

### 3.2 Legal Requirements

We may disclose your information if required by law, court order, or governmental authority, or if we believe disclosure is necessary to protect the rights, property, or safety of our users or others.

### 3.3 Business Transfers

In the event of a merger, acquisition, or sale of assets, your information may be transferred as part of that transaction. We will notify you via email or prominent in-app notice before your data is transferred and becomes subject to a different privacy policy.

---

## 4. Data Storage and Security

Your data is stored on Google Firebase infrastructure, hosted in secure data centers. We implement industry-standard security measures including:

- **Encryption in transit**: all data transmitted between the App and our servers uses TLS/SSL encryption
- **Encryption at rest**: your data is encrypted at rest on Firebase
- **Access controls**: strict role-based access controls limit who can access your data
- **Authentication**: Firebase Authentication manages secure sign-in
- **Security rules**: Firestore Security Rules ensure users can only access their own data

Despite these measures, no method of electronic storage or transmission is 100% secure. We cannot guarantee absolute security, and you use the App at your own risk.

---

## 5. Data Retention

We retain your data for as long as your account is active or as needed to provide the Service. Specifically:

- **Active accounts**: data is retained while your account exists
- **Deleted accounts**: when you delete your account in-app, your financial data, profile, and authentication credentials are deleted immediately as part of that request; we do not hold a further retention window before deletion
- **Data export files**: temporary export archives generated via Settings → Export Data are automatically deleted within 24 hours of creation
- **Subscription and billing transaction records**: retained as required for legal, tax, and accounting compliance, even after account deletion
- **Security audit logs**: retained for a limited period after account deletion for fraud prevention and legal compliance purposes
- **Crash and diagnostic logs**: retained per Firebase Crashlytics' standard retention period

---

## 6. Your Rights and Choices

Depending on your location, you may have the following rights regarding your personal data:

### 6.1 Access
You may request a copy of all personal data we hold about you. You can export your data directly from the App via Settings → Export Data.

### 6.2 Correction
You may update your account information at any time within the App.

### 6.3 Deletion
You may delete your account and all associated data at any time via Settings → Delete Account. Deletion is processed immediately and is permanent and irreversible. If you have an active subscription billed through Apple or Google Play, you must cancel it in your platform's subscription settings before deleting your account, since we cannot cancel platform-billed subscriptions on your behalf.

### 6.4 Data Portability
You may request your data in a structured, machine-readable format via the in-app export feature. Export files are automatically deleted after 24 hours.

### 6.5 Account Security Controls
You may enable or disable optional two-factor authentication (TOTP) at any time via Settings → Security. Crash and diagnostic reporting via Firebase Crashlytics is enabled at all times to help us maintain app stability and cannot be individually disabled within the App.

### 6.6 Marketing Communications
We only send transactional emails (subscription confirmations, payment alerts, security notices). We do not send marketing emails without your explicit consent.

To exercise any of these rights, contact us at dev@eutopiantech.com. We will respond within 30 days.

---

## 7. Children's Privacy

BreadSaver is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If we learn that we have inadvertently collected data from a child under 13, we will promptly delete that information.

If you believe we have collected information from a child under 13, please contact us at dev@eutopiantech.com.

---

## 8. International Data Transfers

BreadSaver is operated from Nigeria. Your data may be processed and stored in the United States (Google Firebase servers) and other countries. By using the App, you consent to the transfer of your information to these countries, which may have different data protection laws than your country of residence.

We ensure that all international transfers comply with applicable data protection laws and that adequate safeguards are in place.

---

## 9. Third-Party Links and Services

The App may contain references to third-party websites or services. This Privacy Policy does not apply to those third parties. We encourage you to review the privacy policies of any third-party services you use.

---

## 10. California Privacy Rights (CCPA)

If you are a California resident, you have the right to:

- Know what personal information we collect, use, disclose, or sell
- Request deletion of your personal information
- Opt out of the sale of your personal information (we do not sell personal information)
- Not be discriminated against for exercising your privacy rights

To submit a California privacy request, contact us at dev@eutopiantech.com.

---

## 11. European Privacy Rights (GDPR)

If you are located in the European Economic Area (EEA), you have additional rights under the General Data Protection Regulation:

- **Right to access**: obtain a copy of your personal data
- **Right to rectification**: correct inaccurate data
- **Right to erasure**: request deletion of your data
- **Right to restriction**: restrict how we process your data
- **Right to data portability**: receive your data in a portable format
- **Right to object**: object to processing based on legitimate interests
- **Right to withdraw consent**: where processing is based on consent

Our lawful bases for processing are: (a) performance of a contract (providing the Service), (b) legitimate interests (improving the App, preventing fraud), and (c) legal obligation (compliance with applicable laws).

To exercise GDPR rights, contact us at dev@eutopiantech.com.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via email or in-app notification at least 14 days before the changes take effect. The "Last updated" date at the top of this page will always reflect the most recent revision.

Your continued use of the App after the effective date of the revised Policy constitutes your acceptance of the changes.

---

## 13. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy, please contact us:

**Eutopian Technologies**
Email: dev@eutopiantech.com
Website: https://eutopiantech.com
