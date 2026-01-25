---
title: "Privacy Policy"
date: 2026-01-11
url: "/daymood/privacy-policy.html"
summary: "How DayMood manages, protects, and uses your personal data."
hidemeta: true
hidden: true
---

**DayMood - Emotional Journal** *Last updated: January 11, 2026*

---

## 1. Data Controller Identity

* **Data Controller:** Jaime López Muñoz
* **Contact email:** [hello@jaimelxpez.com](mailto:hello@jaimelxpez.com)
* **Website:** [jaimelxpez.com](https://jaimelxpez.com/)
* **Purpose:** Development and maintenance of the DayMood application

In compliance with Regulation (EU) 2016/679 of the European Parliament and of the Council, of April 27, 2016 (GDPR), and Organic Law 3/2018, of December 5, on the Protection of Personal Data and guarantee of digital rights (LOPDGDD), we inform you about the processing of your personal data.

## 2. Personal Data We Collect

DayMood collects the following types of data:

### 2.1 Identification data (Google Sign-In)
* Full name
* Email address
* Profile picture (URL)
* Unique user identifier

### 2.2 User content data
* Journal entries (text written by the user)
* Entry titles
* Creation dates

### 2.3 Special category data (Health Data - Art. 9 GDPR)

> **IMPORTANT:** DayMood processes data related to your mental and emotional health, which constitutes a special category of data under Article 9 of the GDPR. This includes:
> * Emotional analysis of your journal entries
> * Identified emotions (based on Plutchik's wheel of emotions)
> * Emotional intensity (scale 1-10)
> * Emotional triggers
> * General mood (positive, negative, mixed, neutral)
> * Clinical context notes
>
> The processing of this data requires your **explicit consent**, which you grant by accepting this policy and using the application.

### 2.4 Technical data
* Application crash and error reports (Firebase Crashlytics)
* Device information (model, operating system version)
* Application preferences (light/dark theme, language)
* API call metadata: endpoint, HTTP method, status code, response times (Firebase Crashlytics and Performance)
* Device and application integrity verification (Firebase App Check with Google Play Integrity)

> **Note on API monitoring:** To ensure service quality, we log technical metadata from our API calls (such as response times and error codes). **We never log the content of your journal entries** in these technical logs, preserving the privacy of your personal information.

## 3. Purpose of Processing

Your personal data will be processed for the following purposes:

| Purpose | Legal Basis |
| :--- | :--- |
| Management of your user account and authentication | Contract performance (Art. 6.1.b GDPR) |
| Storage of your journal entries | Contract performance (Art. 6.1.b GDPR) |
| Emotional analysis through artificial intelligence | Explicit consent (Art. 6.1.a and 9.2.a GDPR) |
| Application improvement and maintenance | Legitimate interest (Art. 6.1.f GDPR) |
| Detection and correction of technical errors | Legitimate interest (Art. 6.1.f GDPR) |

## 4. Third Parties That Process Your Data

To provide the service, we share your data with the following service providers:

| Provider | Service | Shared Data | Location |
| :--- | :--- | :--- | :--- |
| **Google Firebase** | Authentication and storage | Account data, entries, emotions | EU / USA |
| **Google Identity** | Google Sign-In | Authentication credentials | EU / USA |
| **OpenAI** | AI emotional analysis (GPT-4) | Journal entry text | USA |
| **Firebase Crashlytics** | Error reporting and API monitoring | Technical data, API metadata (no content) | EU / USA |
| **Firebase Performance** | Performance metrics | Response times, payload sizes | EU / USA |
| **Google Play Integrity** | Integrity verification | Device and application attestation | EU / USA |

All these providers act as **data processors** and are contractually obligated to protect your data in accordance with GDPR.

## 5. International Data Transfers

> **Important notice:** Your data may be transferred and processed in the United States by Google and OpenAI.

These transfers are made under the following safeguards:
* **Google:** European Commission Standard Contractual Clauses and certification under the EU-US Data Privacy Framework.
* **OpenAI:** European Commission Standard Contractual Clauses and additional security measures.

You can obtain more information about these safeguards by contacting us at the email address indicated.

## 6. Data Retention

| Data Type | Retention Period |
| :--- | :--- |
| User account data | Until you delete your account |
| Journal entries and emotions | Until you delete them or delete your account |
| Application preferences | Until you uninstall the app or clear data |
| Error reports (Crashlytics) | 90 days (Google policy) |
| Performance metrics (Performance) | 90 days (Google policy) |
| Data sent to OpenAI | 30 days (OpenAI API policy) |

## 7. Your Rights

In accordance with GDPR and LOPDGDD, you have the following rights:
* **Right of access:** Know what data we have about you.
* **Right to rectification:** Correct inaccurate or incomplete data.
* **Right to erasure ("right to be forgotten"):** Request the deletion of your data.
* **Right to object:** Object to the processing of your data.
* **Right to restriction:** Request that we limit the processing.
* **Right to data portability:** Receive your data in a structured format.
* **Right to withdraw consent:** You can withdraw your consent at any time.

### How to exercise your rights

You can exercise any of these rights by sending an email to:
**[hello@jaimelxpez.com](mailto:hello@jaimelxpez.com)**

Include in your request:
* Your full name
* The email associated with your DayMood account
* The right you wish to exercise
* Any additional relevant information

We will respond to your request within a maximum of 30 days.

You also have the right to file a complaint with the **Spanish Data Protection Agency (AEPD)**: [www.aepd.es](https://www.aepd.es)

## 8. Account and Data Deletion

You can delete your account and all your data at any time from the "Profile" section of the application, by selecting "Delete account".

When you delete your account:
* All your journal entries will be deleted from our servers
* All associated emotional analyses will be deleted
* Your Firebase Authentication account will be deleted
* Local data on your device will be erased

This process is **irreversible**.

## 9. Data Security

We implement the following security measures to protect your data:
* **Encryption in transit:** All communications use HTTPS/TLS.
* **Encryption at rest:** Local data is stored encrypted (EncryptedSharedPreferences).
* **Certificate Pinning:** Protection against man-in-the-middle attacks.
* **Secure authentication:** Google Sign-In with session tokens.
* **Secure logs:** Automatic redaction of sensitive data in logs. The content of your journal entries is never logged in monitoring logs.
* **Integrity verification:** Firebase App Check with Google Play Integrity verifies that requests come from the legitimate application.

> **End-to-end encryption (E2E)**
>
> **Your privacy is our priority.** The sensitive content of your journal entries is protected with end-to-end encryption:
> * **Algorithm:** AES-256-GCM with 256-bit keys
> * **Encrypted fields:** The text of your entries (*rawEntry*) and the clinical context of each emotion
> * **Key control:** Your encryption key is derived from your Google account and securely stored on your device
> * **Secure sync:** Your data travels encrypted to the cloud; not even we can read the content of your entries
>
> Non-sensitive metadata (title, detected emotions, dates) remains unencrypted to enable search and statistics features.

## 10. Minimum Age

> **DayMood is intended for users 16 years of age or older.**
>
> We do not intentionally collect data from minors under 16 years of age. If you become aware that a minor has provided personal data, please contact us to proceed with its deletion.

## 11. Use of Artificial Intelligence

DayMood uses artificial intelligence (OpenAI GPT-4) to analyze the emotional content of your journal entries. This analysis:
* Is based on the clinical model of Plutchik's Wheel of Emotions
* Identifies emotions, their intensity, and possible triggers
* Provides context for your emotional self-awareness
* **Does NOT replace professional psychological advice**

> **Notice:** Emotional analysis is for guidance only and does not constitute medical or psychological diagnosis. If you experience mental health issues, please consult a qualified professional.

## 12. Modifications to this Policy

We reserve the right to modify this Privacy Policy. In case of significant changes:
* We will update the "last updated" date
* We may notify you through the application
* Continued use of the application after changes implies your acceptance

We recommend reviewing this policy periodically.

## 13. Contact

For any questions related to this Privacy Policy or the processing of your data:

* **Email:** [hello@jaimelxpez.com](mailto:hello@jaimelxpez.com)
* **Website:** [jaimelxpez.com](https://jaimelxpez.com/)
* **Data Controller:** Jaime López Muñoz
