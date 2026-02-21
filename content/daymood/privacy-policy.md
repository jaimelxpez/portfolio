---
title: "Privacy Policy"
date: 2026-02-20
url: "/daymood/privacy-policy.html"
summary: "How DayMood manages, protects, and uses your personal data."
hidemeta: true
hidden: true
---

**DayMood - Emotional Journal** *Last updated: February 20, 2026*

---

## 1. Data Controller Identity

* **Data Controller:** Jaime López Muñoz
* **Contact Email:** [daymood@jaimelxpez.com](mailto:daymood@jaimelxpez.com)
* **Website:** [jaimelxpez.com](https://jaimelxpez.com/)
* **Purpose:** Development and maintenance of the DayMood application

In compliance with Regulation (EU) 2016/679 of the European Parliament and of the Council of 27 April 2016 (General Data Protection Regulation, "GDPR"), we inform you about the processing of your personal data.

## 2. Personal Data We Collect

DayMood collects the following types of data:

### 2.1 Identification Data (platform-specific)

**Available authentication methods:**
* **Android:** Google Sign-In
* **iOS:** Apple Sign-In, Google Sign-In, or Email/Password

Data collected during authentication:
* Full name
* Email address
* Profile picture (URL, if available)
* Unique user identifier

### 2.2 User Content Data
* Diary entries (text written by the user)
* Entry titles
* Creation dates

### 2.3 Special Category Data (Health Data - Art. 9 GDPR)

> **IMPORTANT:** DayMood processes data relating to your mental and emotional health, which constitutes a special category of data under Article 9 of the GDPR. This data is collected **exclusively** to provide you with emotional self-awareness insights based on your diary entries. Specifically, this includes:
> * Emotional analysis of your diary entries
> * Identified emotions (based on Plutchik's Wheel of Emotions)
> * Emotional intensity (scale 1-10)
> * Emotional triggers
> * Overall mood (positive, negative, mixed, neutral)
> * Clinical context notes
>
> Processing of this data requires your **explicit consent**, which you provide by accepting this policy and actively using the emotional analysis feature of the application. You may withdraw this consent at any time (see Section 7).
>
> **This data is used solely for your personal emotional self-awareness and is never used for medical or psychological diagnosis. DayMood does not provide medical advice, diagnoses, or treatment recommendations.**

### 2.4 Technical Data
* Error and crash reports (Firebase Crashlytics)
* Device information (model, operating system version)
* App preferences (light/dark theme, language)
* API call metadata: endpoint, HTTP method, status code, response times (Firebase Crashlytics and Performance)
* Device and app integrity verification (Firebase App Check)

### 2.5 Subscription and Payment Data
* Subscription status (free or premium)
* Subscription plan type (monthly, annual)
* Purchase tokens (managed by Google Play on Android and Apple App Store on iOS)
* Transaction dates and renewal periods

> **Note on Payment Data:** DayMood does not directly process, store, or have access to your credit card numbers, bank account information, or any other payment method details. All payment processing is handled securely by **Google Play** (on Android) and **Apple App Store** (on iOS). We only receive confirmation of your subscription status and transaction identifiers. Neither the Developer nor the Application has access to your full payment credentials at any time.

> **Note on API Monitoring:** To ensure service quality, we record technical metadata of API calls (such as response times and error codes). **We never record the content of your diary entries** in these technical logs, preserving the privacy of your personal information.

### 2.6 Advertising Data (Free Tier Only)

* Advertising identifier (Google Advertising ID on Android; IDFA on iOS, only if you grant permission through App Tracking Transparency)
* Device information for ad serving (device model, OS version, screen size)
* Ad interaction data (impressions, clicks)

> **iOS Users — App Tracking Transparency (ATT):** On iOS, DayMood will request your permission through Apple's App Tracking Transparency framework before accessing your device's advertising identifier (IDFA) for personalized advertising. If you decline, only non-personalized ads will be shown. You can change this setting at any time in your device's Settings > Privacy & Security > Tracking.
>
> **Android Users:** You can opt out of personalized advertising by enabling "Opt out of Ads Personalization" in your device's Google Settings.
>
> Advertising is displayed **only in the free tier**. Premium subscribers do not see any ads, and no advertising data is collected from Premium users.

## 3. Purpose of Processing

Your personal data will be processed for the following purposes:

| Purpose | Legal Basis |
| :--- | :--- |
| User account management and authentication | Contract performance (Art. 6.1.b GDPR) |
| Storage of your diary entries | Contract performance (Art. 6.1.b GDPR) |
| Emotional analysis using artificial intelligence | Explicit consent (Art. 6.1.a and Art. 9.2.a GDPR) |
| App improvement and maintenance | Legitimate interest (Art. 6.1.f GDPR) |
| Technical error detection and correction | Legitimate interest (Art. 6.1.f GDPR) |
| Subscription management and payment processing | Contract performance (Art. 6.1.b GDPR) |
| Displaying personalized advertising (free tier only, iOS with ATT consent) | Consent (Art. 6.1.a GDPR) on iOS via ATT; Legitimate interest (Art. 6.1.f GDPR) on Android with opt-out available |
| Displaying non-personalized advertising (free tier only) | Legitimate interest (Art. 6.1.f GDPR) |

## 4. Third Parties Processing Your Data

To provide the service, we share your data with the following service providers:

| Provider | Service | Shared Data | Location |
| :--- | :--- | :--- | :--- |
| **Google Firebase** | Authentication and storage | Account data, diary entries, emotions | EU / USA |
| **Google Identity** | Sign-in (Android and iOS) | Authentication credentials | EU / USA |
| **Apple Sign-In** | Sign-in (iOS only) | Authentication credentials | EU / USA |
| **Google Gemini** | AI emotional analysis (primary provider) | Diary entry text (sent for processing; Google may retain this data for up to 30 days in accordance with Google's terms of service) | EU / USA |
| **OpenAI** | AI emotional analysis (backup provider) and OCR cleanup (Android) | Diary entry text (sent for processing; OpenAI may retain this data for up to 30 days in accordance with OpenAI's API data usage policy) | USA |
| **Google ML Kit** | Optical character recognition (Android only) | Images for text extraction (processed entirely on-device; no data is sent to external servers) | On-device |
| **Apple Vision Framework** | Optical character recognition (iOS only) | Images for text extraction (processed entirely on-device; no data is sent to external servers) | On-device |
| **Firebase Crashlytics** | Error reporting and API monitoring | Technical device data, API metadata (no diary content) | EU / USA |
| **Firebase Performance** | Performance metrics | Response times, payload sizes | EU / USA |
| **Firebase App Check** | Integrity verification (Play Integrity on Android, App Attest/DeviceCheck on iOS) | Device and app attestation tokens | EU / USA |
| **Google Play Billing** | Subscription and payment processing (Android) | Purchase tokens, subscription status, transaction IDs | EU / USA |
| **Apple App Store / StoreKit** | Subscription and payment processing (iOS) | Purchase tokens, subscription status, transaction IDs | EU / USA |
| **Google AdMob** | Advertising (free tier only) | Advertising ID (IDFA on iOS only with ATT consent; Google Advertising ID on Android), device information | EU / USA |

All these providers act as **data processors** and are contractually obligated to protect your data in accordance with the GDPR. Each provider processes your data in accordance with their respective terms of service and privacy policies.

## 5. International Data Transfers

> **Important notice:** Your data may be transferred and processed in the United States by Google, Apple, and OpenAI.

These transfers are made under the following safeguards:
* **Google** (Firebase, Gemini, ML Kit cloud services, AdMob, Play Billing)**:** European Commission Standard Contractual Clauses and certification under the EU-US Data Privacy Framework.
* **Apple** (Sign-In, App Store payments, Vision Framework, App Attest)**:** European Commission Standard Contractual Clauses and additional security measures implemented by Apple.
* **OpenAI** (GPT-4o emotional analysis and OCR cleanup)**:** European Commission Standard Contractual Clauses and additional security measures.

You can obtain more information about these safeguards by contacting us at the email provided.

## 6. Data Retention

| Data Type | Retention Period |
| :--- | :--- |
| User account data | Until you delete your account |
| Diary entries and emotions | Until you delete them or delete your account |
| App preferences | Until you uninstall the app or clear data |
| Crash reports (Firebase Crashlytics) | 90 days, in accordance with Google's data retention policies for Firebase Crashlytics |
| Performance metrics (Firebase Performance) | 90 days, in accordance with Google's data retention policies for Firebase Performance |
| Data sent to Google Gemini | Google may retain your text for up to 30 days in accordance with Google's terms of service for the Gemini API |
| Data sent to OpenAI | OpenAI may retain your text for up to 30 days in accordance with OpenAI's API data usage policy |
| Subscription and payment data (Google Play) | Duration of the subscription plus the legal retention period required for tax and accounting obligations, in accordance with Google Play's terms of service |
| Subscription and payment data (Apple App Store) | Duration of the subscription plus the legal retention period required for tax and accounting obligations, in accordance with Apple's terms and conditions for App Store purchases |
| Advertising data (AdMob) | Until you subscribe to Premium, revoke ATT consent (iOS), opt out of personalized ads (Android), or uninstall the app. Google may retain aggregated advertising data in accordance with Google AdMob's terms of service |

> **Note:** Retention periods for third-party providers are determined by each provider's terms of service and data retention policies. DayMood does not control how long third-party providers retain data beyond what is specified in their respective agreements. We encourage you to review the privacy policies and terms of service of each provider listed in Section 4.

## 7. Your Rights

Under the GDPR, you have the following rights:
* **Right of access:** Know what data we have about you.
* **Right to rectification:** Correct inaccurate or incomplete data.
* **Right to erasure ("right to be forgotten"):** Request deletion of your data.
* **Right to object:** Object to the processing of your data (including objecting to non-personalized advertising).
* **Right to restriction:** Request that we limit the processing.
* **Right to data portability:** Receive your data in a structured, commonly used, and machine-readable format.
* **Right to withdraw consent:** You can withdraw your consent for emotional analysis or personalized advertising at any time, without affecting the lawfulness of processing based on consent before its withdrawal.

### How to Exercise Your Rights

You can exercise any of these rights by sending an email to:
**[daymood@jaimelxpez.com](mailto:daymood@jaimelxpez.com)**

Include in your request:
* Your full name
* The email associated with your DayMood account
* The right you wish to exercise
* Any additional relevant information

We will respond to your request within a maximum of 30 days. If the complexity of the request requires it, this period may be extended by a further two months, in which case we will inform you within the first 30 days.

You also have the right to file a complaint with the **Spanish Data Protection Agency (AEPD)**: [www.aepd.es](https://www.aepd.es), or with your local data protection authority.

## 8. Account and Data Deletion

You can delete your account and all your data at any time from the "Profile" section of the app, selecting "Delete account".

When you delete your account:
* All your diary entries will be deleted from our servers
* All associated emotional analyses will be deleted
* Your Firebase Authentication account will be deleted
* Local data on your device will be erased

This process is **irreversible**.

> **Note:** Deletion of your account data from DayMood's servers does not affect data already processed by third-party providers (Google Gemini, OpenAI, Firebase Crashlytics, etc.), which is subject to each provider's data retention policies as described in Section 6. Subscription data may be retained by Google Play or Apple App Store in accordance with their respective terms of service and applicable tax regulations.

## 9. Data Security

We implement the following security measures to protect your data:
* **Encryption in transit:** All communications use HTTPS/TLS.
* **Encryption at rest:** Local data is stored encrypted (EncryptedSharedPreferences on Android, Keychain + Secure Enclave on iOS).
* **Certificate Pinning:** Protection against man-in-the-middle attacks.
* **Secure authentication:** Google Sign-In / Apple Sign-In / Email with session tokens.
* **Secure logs:** Automatic redaction of sensitive data in logs. Your diary entry content is never recorded in monitoring logs.
* **Integrity verification:** Firebase App Check verifies that requests come from the legitimate application (Play Integrity on Android, App Attest on iOS).

> **End-to-End Encryption (E2E)**
>
> **Your privacy is our priority.** The sensitive content of your diary entries is protected with end-to-end encryption:
> * **Algorithm:** AES-256-GCM with 256-bit keys
> * **Encrypted fields:** The text of your entries (*rawEntry*) and the clinical context of each emotion
> * **Key control:** Your encryption key is derived from your account and stored securely on your device
> * **Secure sync:** Your data travels encrypted to the cloud; not even we can read the content of your entries
>
> Non-sensitive metadata (title, detected emotions, dates) remain unencrypted to enable search and statistics features.

> **3-Layer Privacy Firewall**
>
> DayMood implements a **defense-in-depth** system that makes it physically impossible for your entry content to leak through logs or monitoring systems:
> * **Layer 1 - HTTP Redaction:** All entry content is redacted before any network logging
> * **Layer 2 - SDK Protection:** Security guards for third-party SDKs
> * **Layer 3 - Analytics Filter:** Real-time validation of all events before sending

## 10. Minimum Age

> **DayMood is intended for users aged 16 and over.**
>
> We do not intentionally collect data from minors under 16 years of age. If you become aware that a minor has provided personal data, please contact us to proceed with its deletion.

## 11. Use of Artificial Intelligence

DayMood uses artificial intelligence to analyze the emotional content of your diary entries:
* **Primary provider:** Google Gemini 2.5 Pro, optimized for deep clinical analysis
* **Backup provider:** OpenAI GPT-4o, for greater service availability

This analysis:
* Is based on Plutchik's Wheel of Emotions clinical model
* Identifies emotions, their intensity, and possible triggers
* Provides context for your emotional self-awareness

> **IMPORTANT — Limitations of Artificial Intelligence:**
>
> * The emotional analysis provided by DayMood is **for guidance and self-awareness purposes only**.
> * DayMood **does NOT provide medical or psychological diagnoses**, and the AI analysis **does NOT constitute medical advice, psychological counseling, or any form of healthcare service**.
> * The AI may produce inaccurate, incomplete, or inconsistent results. Emotional analysis is inherently subjective and the AI's output should not be relied upon as a definitive assessment of your emotional state.
> * DayMood is **NOT a substitute for professional psychological or medical advice, diagnosis, or treatment**. If you experience mental health issues, depression, anxiety, suicidal thoughts, or other conditions, please consult a qualified mental health professional immediately.
> * **In case of emergency or mental health crisis, immediately contact emergency services (112 in Europe, 911 in the USA) or crisis helplines in your country.**

### 11.1 How AI Processes Your Data

* Your diary entry text is sent to the AI provider (Google Gemini or OpenAI) via encrypted connection (HTTPS/TLS) for emotional analysis.
* The AI provider processes your text and returns the emotional analysis results.
* Google Gemini may retain your text for up to 30 days in accordance with Google's terms of service.
* OpenAI may retain your text for up to 30 days in accordance with OpenAI's API data usage policy.
* DayMood does not use your data to train AI models. Refer to each provider's terms of service for their data usage practices.

## 12. Advertising

DayMood displays advertising through Google AdMob **only for users on the free tier**. Premium subscribers do not see any ads.

### 12.1 App Tracking Transparency (iOS)

On iOS devices, DayMood complies with Apple's App Tracking Transparency (ATT) framework:
* Before collecting your advertising identifier (IDFA), DayMood will display Apple's ATT permission prompt.
* If you **allow** tracking, personalized ads may be shown based on your advertising identifier.
* If you **deny** tracking or have enabled "Limit Ad Tracking" in your device settings, only non-personalized, contextual ads will be shown.
* You can change your tracking preference at any time in **Settings > Privacy & Security > Tracking** on your iOS device.

### 12.2 Personalized Advertising Opt-Out (Android)

On Android devices, you can opt out of personalized advertising by going to **Settings > Google > Ads > Opt out of Ads Personalization**.

### 12.3 Data Shared with AdMob

Google AdMob may receive device information and advertising identifiers (subject to your consent on iOS) to serve ads. Google processes this data in accordance with [Google's Privacy Policy](https://policies.google.com/privacy). DayMood does **not** share your diary entries, emotional analyses, or any health-related data with advertising providers.

## 13. Apple Health and HealthKit

> **DayMood does NOT access, read, write, or integrate with Apple HealthKit or Apple Health in any way.** Although DayMood processes emotional and mood data, this data is managed entirely within DayMood's own infrastructure and is not shared with or stored in Apple's Health ecosystem.

## 14. App Store Privacy Information (Nutrition Labels)

In compliance with Apple's App Store requirements, below is a summary of how DayMood's data practices correspond to the App Store Privacy "Nutrition Labels":

**Data Used to Track You:**
* Advertising identifier (IDFA) — only if you grant ATT permission on iOS, used by Google AdMob for personalized advertising in the free tier.

**Data Linked to You:**
* Contact information (name, email address) — for account creation and authentication.
* User content (diary entries) — for providing the core journaling and emotional analysis service.
* Health & Fitness data (emotional analysis results) — for providing emotional self-awareness insights.
* Identifiers (user ID) — for account management.
* Purchase history (subscription status) — for managing Premium access.

**Data Not Linked to You:**
* Crash data (Firebase Crashlytics) — for app stability and error diagnosis.
* Performance data (Firebase Performance) — for monitoring app responsiveness.
* Diagnostics (device and app attestation via Firebase App Check) — for security verification.

> This summary is provided for transparency purposes. For the complete and authoritative description of our data practices, please refer to the full sections of this Privacy Policy.

## 15. Supported Platforms

DayMood is available on the following platforms:

| Platform | Requirements | Availability |
| :--- | :--- | :--- |
| **Android** | Android 10 or higher (API 29+) | Google Play Store |
| **iOS** | iOS 17.0 or higher | Apple App Store |

This Privacy Policy applies to all versions of the application, regardless of the platform used. Both platforms share the same Firebase database and the same security and privacy guarantees.

## 16. Changes to This Policy

We reserve the right to modify this Privacy Policy. In case of significant changes:
* We will update the "last updated" date
* We may notify you through the application
* Continued use of the application after changes implies your acceptance

We recommend reviewing this policy periodically.

## 17. Contact

For any questions related to this Privacy Policy or the processing of your data:

* **Email:** [daymood@jaimelxpez.com](mailto:daymood@jaimelxpez.com)
* **Website:** [jaimelxpez.com](https://jaimelxpez.com/)
* **Data Controller:** Jaime López Muñoz
