# Privacy Policy for Boli Boost

**Last Updated:** September 21, 2026  
**Effective Date:** September 21, 2026  
**Application Name:** Boli Boost  
**Package Identifier:** `dev.soraatelier.boliboost`  
**Developer / Publisher:** Sora Atelier  
**Contact Email:** [contact@soraatelier.dev](mailto:contact@soraatelier.dev)

---

## 1. Introduction

Welcome to **Boli Boost**, an interactive French language-learning application designed for children, students, and language learners of all ages. 

Sora Atelier ("we", "our", or "us") is dedicated to protecting the privacy of our users, especially children. This Privacy Policy outlines how our application treats user information and explains our commitment to compliance with the **Children's Online Privacy Protection Act (COPPA)**, the **EU General Data Protection Regulation (GDPR / GDPR-K)**, and the **Google Play Families Policy**.

---

## 2. Information We Do NOT Collect

We believe in privacy by design. **Boli Boost does not collect, store, or transmit any Personally Identifiable Information (PII)**. Specifically:

- We do **not** collect names, email addresses, physical addresses, or phone numbers.
- We do **not** collect precise or approximate geographic location data.
- We do **not** collect or access device contacts, photos, or media files.
- We do **not** collect or transmit the **Android Advertising ID (AAID)**. The `com.google.android.gms.permission.AD_ID` permission is explicitly blocked and removed from our application manifest.
- We do **not** use third-party analytics, behavioral tracking, or session recording SDKs (e.g., Firebase Analytics, Adjust, AppsFlyer).

---

## 3. Microphone & Audio Processing (`RECORD_AUDIO`)

Boli Boost features interactive voice activities where learners practice French pronunciation (such as repeating alphabet sounds, numbers, and vocabulary).

- **Purpose:** The microphone permission is requested solely to provide real-time feedback on French pronunciation.
- **Ephemeral & Local Processing:** Audio captured through the microphone is processed **ephemerally in-memory** on your device using native platform speech recognition services (`android.speech.RecognitionService`).
- **No Remote Storage or Transmission:** Voice recordings are **never recorded to disk, never uploaded to any remote server, never shared with third parties, and never used for voice identification or AI model training**.
- **Immediate Disposal:** As soon as the pronunciation similarity score is calculated, the audio buffer is immediately discarded from memory.
- **Alternative Mode:** If microphone permission is declined or unavailable, users can still complete all exercises using the manual self-confirmation buttons.

---

## 4. Local Data Storage

All learning progress, including:
- Completed lessons and unlocked levels
- Quiz scores and best attempts
- Daily speaking challenge streaks

is stored **exclusively locally on your device** using standard local storage (`localStorage`). This data never leaves your device and is not synced to external cloud databases.

---

## 5. Advertising Policy & Child Protections

- **Initial Release:** This release of Boli Boost is **100% ad-free**. There are no third-party advertisements displayed in the application.
- **Future Updates:** If child-friendly advertisements are introduced in future versions:
  1. Only ad networks certified under the **Google Play Certified Families Self-Certified Ad Network** program will be used.
  2. All ad requests will strictly enforce child-directed flags (`tagForChildDirectedTreatment: true`, `tagForUnderAgeOfConsent: true`, and `MaxAdContentRating: General`).
  3. Ad personalization and behavioral tracking will remain permanently disabled (`npa: true`).
  4. Intrusive formats (such as non-skippable interstitials or pop-ups) will never be used.

---

## 6. Children's Privacy (COPPA & GDPR-K Compliance)

Because our application is designed for children:
- We do not require account creation, registration, or login.
- We do not knowingly collect personal data from children under the age of 13 (or under 16 in the European Economic Area).
- We do not condition a child's participation in any activity on the disclosure of more personal information than is necessary.
- Parents and legal guardians can easily clear all locally saved game progress at any time by clearing the app data in Android Settings or uninstalling the app.

---

## 7. Data Retention and Deletion

Because we do not collect or store personal data on remote servers:
- We have no personal data retention schedules.
- To delete all stored learning progress and cached assets, simply clear the app storage in your device settings:
  `Settings > Apps > Boli Boost > Storage > Clear Data`
  or uninstall the app from your device.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect enhancements to our features or regulatory requirements. Any updates will be posted to this page with an updated "Last Updated" date. We encourage parents and users to review this policy periodically.

---

## 9. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or the privacy practices of Boli Boost, please contact us:

- **Developer:** Sora Atelier
- **Email:** [contact@soraatelier.dev](mailto:contact@soraatelier.dev)
- **Website:** [https://soraatelier.dev](https://soraatelier.dev)
