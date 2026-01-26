---
title: "Privacy Policy"
date: 2026-01-25
url: "/daymood/privacy-policy.html"
summary: "How DayMood manages, protects, and uses your personal data."
hidemeta: true
hidden: true
---

**DayMood - Emotional Journal** *Last updated: January 25, 2026*

---

## 1. Data Controller Identity

* **Data Controller:** Jaime Lopez Munoz
* **Contact Email:** [hello@jaimelxpez.com](mailto:hello@jaimelxpez.com)
* **Website:** [jaimelxpez.com](https://jaimelxpez.com/)
* **Purpose:** Development and maintenance of the DayMood application

In compliance with Regulation (EU) 2016/679 of the European Parliament and of the Council of 27 April 2016 (GDPR), we inform you about the processing of your personal data.

## 2. Personal Data We Collect

DayMood collects the following types of data:

### 2.1 Identification Data (platform-specific)

**Available authentication methods:**
* **All platforms:** Google Sign-In or Email/Password
* **iOS only:** Apple Sign-In

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

> **IMPORTANT:** DayMood processes data relating to your mental and emotional health, which constitutes a special category of data under Article 9 of the GDPR. This includes:
> * Emotional analysis of your diary entries
> * Identified emotions (based on Plutchik's Wheel of Emotions)
> * Emotional intensity (scale 1-10)
> * Emotional triggers
> * Overall mood (positive, negative, mixed, neutral)
> * Clinical context notes
>
> Processing of this data requires your **explicit consent**, which you provide by accepting this policy and using the application.

### 2.4 Technical Data
* Error and crash reports (Firebase Crashlytics)
* Device information (model, operating system version)
* App preferences (light/dark theme, language)
* API call metadata: endpoint, HTTP method, status code, response times (Firebase Crashlytics and Performance)
* Device and app integrity verification (Firebase App Check)

> **Note on API Monitoring:** To ensure service quality, we record technical metadata of API calls (such as response times and error codes). **We never record the content of your diary entries** in these technical logs, preserving the privacy of your personal information.

## 3. Purpose of Processing

Your personal data will be processed for the following purposes:

| Purpose | Legal Basis |
| :--- | :--- |
| User account management and authentication | Contract performance (Art. 6.1.b GDPR) |
| Storage of your diary entries | Contract performance (Art. 6.1.b GDPR) |
| Emotional analysis using artificial intelligence | Explicit consent (Art. 6.1.a and 9.2.a GDPR) |
| App improvement and maintenance | Legitimate interest (Art. 6.1.f GDPR) |
| Technical error detection and correction | Legitimate interest (Art. 6.1.f GDPR) |

## 4. Third Parties Processing Your Data

To provide the service, we share your data with the following service providers:

| Provider | Service | Shared Data | Location |
| :--- | :--- | :--- | :--- |
| **Google Firebase** | Authentication and storage | Account data, diary entries, emotions | EU / USA |
| **Google Identity** | Sign-in (all platforms) | Authentication credentials | EU / USA |
| **Apple Sign-In** | Sign-in (iOS only) | Authentication credentials | EU / USA |
| **Google Gemini** | AI emotional analysis (primary provider) | Diary entry text | EU / USA |
| **OpenAI** | AI emotional analysis (backup provider) | Diary entry text | USA |
| **Google ML Kit** | Optical character recognition (Android only) | Images for text extraction | On-device |
| **Apple Vision Framework** | Optical character recognition (iOS only) | Images for text extraction | On-device |
| **Firebase Crashlytics** | Error reporting and API monitoring | Technical device data, API metadata (no content) | EU / USA |
| **Firebase Performance** | Performance metrics | Response times, payload sizes | EU / USA |
| **Firebase App Check** | Integrity verification (Play Integrity on Android, App Attest/DeviceCheck on iOS) | Device and app attestation | EU / USA |

All these providers act as **data processors** and are contractually obligated to protect your data in accordance with the GDPR.

## 5. International Data Transfers

> **Important notice:** Your data may be transferred and processed in the United States by Google, Apple, and OpenAI.

These transfers are made under the following safeguards:
* **Google:** European Commission Standard Contractual Clauses and certification under the EU-US Data Privacy Framework.
* **Apple:** European Commission Standard Contractual Clauses and additional security measures.
* **OpenAI:** European Commission Standard Contractual Clauses and additional security measures.

You can obtain more information about these safeguards by contacting us at the email provided.

## 6. Data Retention

| Data Type | Retention Period |
| :--- | :--- |
| User account data | Until you delete your account |
| Diary entries and emotions | Until you delete them or delete your account |
| App preferences | Until you uninstall the app or clear data |
| Crash reports (Crashlytics) | 90 days (Google policy) |
| Performance metrics (Performance) | 90 days (Google policy) |
| Data sent to Google Gemini | 30 days (Google policy) |
| Data sent to OpenAI | 30 days (OpenAI API policy) |

## 7. Your Rights

Under the GDPR, you have the following rights:
* **Right of access:** Know what data we have about you.
* **Right to rectification:** Correct inaccurate or incomplete data.
* **Right to erasure ("right to be forgotten"):** Request deletion of your data.
* **Right to object:** Object to the processing of your data.
* **Right to restriction:** Request that we limit the processing.
* **Right to data portability:** Receive your data in a structured format.
* **Right to withdraw consent:** You can withdraw your consent at any time.

### How to Exercise Your Rights

You can exercise any of these rights by sending an email to:
**[hello@jaimelxpez.com](mailto:hello@jaimelxpez.com)**

Include in your request:
* Your full name
* The email associated with your DayMood account
* The right you wish to exercise
* Any additional relevant information

We will respond to your request within a maximum of 30 days.

You also have the right to file a complaint with the **Spanish Data Protection Agency (AEPD)**: [www.aepd.es](https://www.aepd.es), or with your local data protection authority.

## 8. Account and Data Deletion

You can delete your account and all your data at any time from the "Profile" section of the app, selecting "Delete account".

When you delete your account:
* All your diary entries will be deleted from our servers
* All associated emotional analyses will be deleted
* Your Firebase Authentication account will be deleted
* Local data on your device will be erased

This process is **irreversible**.

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
* **Does NOT replace professional psychological advice**

> **Notice:** The emotional analysis is for guidance only and does not constitute medical or psychological diagnosis. If you experience mental health issues, please consult a qualified professional.

## 12. Supported Platforms

DayMood is available on the following platforms:

| Platform | Requirements | Availability |
| :--- | :--- | :--- |
| **Android** | Android 10 or higher (API 29+) | Google Play Store |
| **iOS** | iOS 17.0 or higher | Apple App Store |

This Privacy Policy applies to all versions of the application, regardless of the platform used. Both platforms share the same Firebase database and the same security and privacy guarantees.

## 13. Changes to This Policy

We reserve the right to modify this Privacy Policy. In case of significant changes:
* We will update the "last updated" date
* We may notify you through the application
* Continued use of the application after changes implies your acceptance

We recommend reviewing this policy periodically.

## 14. Contact

For any questions related to this Privacy Policy or the processing of your data:

* **Email:** [hello@jaimelxpez.com](mailto:hello@jaimelxpez.com)
* **Website:** [jaimelxpez.com](https://jaimelxpez.com/)
* **Data Controller:** Jaime Lopez Munoz
