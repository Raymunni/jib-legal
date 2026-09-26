# Privacy Policy for Jib

**Last updated: 26 September 2026**

This policy explains what information Jib ("the App", "we", "us") collects, how it's used, and the choices you have. It applies to the Jib mobile application, published under the package name `com.jibjobs.app`, and to Jib on the web at [jibapp.xyz/web](https://jibapp.xyz/web/), which lets you sign in and manage the same account from a browser.


---

## 1. Who we are

Jib is developed by Thomas Horsey. For any privacy questions or requests, contact: hello@jibapp.xyz.

## 2. Information we collect

### 2.1 Account information
Jib offers three ways to sign in: Google, Apple, and email/password.
- **Google or Apple Sign-In:** we receive your name and email address from Google or Apple (and a profile photo, for Google), and a unique account identifier (via Firebase Authentication).
- **Email/password:** we receive the email address and password you provide; the password is stored and verified by Firebase Authentication, not by us directly, and we never see it in plain text.

You can also use the app without signing in at all; in that case your data stays only on your device and is not backed up to the cloud.

### 2.2 Content you create
This is the core of what the app stores, and it can include:
- House, space, and job details you enter (names, descriptions, notes, recurrence schedules)
- Photos you take or upload of your house, spaces, and jobs, including "before and after" photo pairs
- Shopping list items, including any retailer names or links you enter
- Your suburb/location, entered manually or resolved from your device's location (used to generate location-aware advice — see Section 4)
- Free-form questions and messages you send to the AI planning feature, and the AI's responses

### 2.3 Automatically collected information
- **Usage analytics and crash reports.** We use Google Analytics for Firebase and Firebase Crashlytics to understand how the app is used and to fix bugs: for example app opens, screens viewed, which features are used (such as creating or completing a job, using an AI feature, or viewing the subscription screen), purchases and subscription status, crash details, device model, operating system and app version, and approximate location (country/region). These are linked to a random account identifier and an app-instance identifier, not to your name or email address, and are not used for advertising.
- Location data, only if you grant location permission, and only to resolve your suburb for climate/planning context — we do not track or store precise ongoing location

### 2.4 Purchases and subscriptions
If you buy a premium subscription or AI credit top-up, the purchase itself is handled entirely by Google Play or the Apple App Store — we never see or store your payment card details. To manage entitlements (what you've bought and whether it's still active), we use RevenueCat, which receives your purchase/subscription status and a device identifier from the App Store or Play Store, not your card details. See [RevenueCat's Privacy Policy](https://www.revenuecat.com/privacy) for details. We do not knowingly collect information from children — see Section 9.

## 3. How we use your information

We use the information above to:
- Provide the core functionality of the app — storing your houses, spaces, jobs, photos, and shopping lists, and syncing them across your devices when you're signed in
- Generate AI-powered job plans, step-by-step directions, shopping suggestions, and safety warnings (see Section 4)
- Generate a general climate/soil/building-context summary for your suburb
- Maintain and improve the app, including diagnosing bugs
- Communicate with you about your account, if you contact us

We do not sell your personal information, and we do not use it for advertising. Jib does not currently display any ads.

## 4. AI features and third-party processing

Jib uses Anthropic's Claude API to power job planning, step generation, shopping suggestions, and follow-up questions. When you use these features, the relevant job details you've entered (title, description, room, and — where relevant — a photo you've attached) are sent to Anthropic to generate a response. Anthropic's own privacy practices govern how they handle that data in transit and processing; see [Anthropic's Privacy Policy](https://www.anthropic.com/legal/privacy) for details.

**Important — AI-generated content is not professional advice.** The steps, material suggestions, cost estimates, and safety warnings the AI provides are generated automatically and may be incomplete, inaccurate, or fail to identify every risk specific to your property. AI-generated safety warnings are a helpful prompt, not a substitute for judgment or professional inspection. See the in-app Terms of Service for the full disclaimer on this — it matters, and we'd rather say it twice than not enough.

## 5. Where your information is stored

- **On your device:** house, space, job, and shopping data, and photos, are stored locally on your device at all times.
- **In the cloud (only if signed in):** if you sign in — with Google, Apple, or email/password — this same data is also synced to Google Firebase services (Firestore for structured data, Firebase Storage for photos) so it's available if you switch devices or reinstall the app. This data is associated with your account and is not accessible to other users.
- **Location/suburb lookups:** resolving a suburb from your device location or a text search uses Google's geocoding and Places services, and (for AI-assisted matching) Anthropic's API. Neither retains this beyond what's needed to return a result.

## 6. Sharing your information

We don't sell or rent your information. We share it only with the service providers necessary to run the app:
- **Google Firebase** (Authentication, Firestore, Storage, Google Analytics for Firebase, Crashlytics) — to sign you in (including via Google or Apple), sync your data, measure app usage and diagnose crashes
- **Apple** — only if you choose Sign in with Apple, to authenticate you
- **Anthropic** — to power AI planning features, as described in Section 4
- **Google Places / geocoding services** — to resolve suburb and location information
- **RevenueCat** — to manage subscription and credit purchases, as described in Section 2.4. RevenueCat receives your random account identifier so purchases can be matched to your account, and shares purchase events (such as a trial starting or a subscription renewing) with our Google Analytics for Firebase property.

We may also disclose information if required by law, or to protect the rights, safety, or property of Jib, our users, or others.

## 7. Your choices and rights

- **Access and correction:** you can view and edit almost all of your data directly within the app at any time.
- **Deletion:** you can delete individual jobs, photos, spaces, or houses from within the app. You can also delete your entire account, which permanently removes your cloud-synced data, from Settings.
- **Local-only use:** you can use the app without signing in, in which case no data leaves your device.
- **Location permission:** you can decline or revoke location permission at any time in your device settings; the app will fall back to manual suburb search.

If you're in the EU/UK, you also have rights under GDPR (access, rectification, erasure, portability, and objection to processing) — contact us using the details in Section 1 to exercise these. If you're in Australia, we aim to handle your information consistently with the Australian Privacy Principles.

## 8. Data retention

We retain your account data for as long as your account is active. If you delete your account, your cloud-synced data is permanently removed. Data that remains only on your device is retained until you delete the app or clear its data.

## 9. Children's privacy

Jib is not directed at children, and we do not knowingly collect information from anyone under 16. If you believe a child has provided us with personal information, please contact us and we'll remove it.

## 10. Security

We use industry-standard measures (including Firebase's built-in security features) to protect your information. No method of transmission or storage is 100% secure, and we can't guarantee absolute security.

## 11. Changes to this policy

We may update this policy from time to time. Material changes will be reflected by updating the "Last updated" date above, and — where required by law — we'll provide additional notice.

## 12. Contact us

Questions about this policy or your data: hello@jibapp.xyz.
