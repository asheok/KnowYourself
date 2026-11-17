# Privacy Policy for KnowYourself

**Last Updated:** November 17, 2026  
**Effective Date:** November 17, 2026

KnowYourself ("we", "our", or "the App") was created with a fundamental conviction: **your most intimate thoughts, voice reflections, and mental well-being belong exclusively to you.** 

This Privacy Policy explains our zero-knowledge architecture and details how your data is handled when you use the KnowYourself application on iOS.

---

## 1. Zero-Knowledge Architecture (Our Core Principle)

* **No Cloud Transmission:** KnowYourself does not operate external databases, user accounts, or analytical tracking servers.
* **No Telemetry or Ad Networks:** We do not track user behavior, use third-party analytics trackers, or show advertisements.
* **100% On-Device Processing:** All speech transcription and AI cognitive reasoning occur entirely on your Apple Silicon hardware using Apple's Neural Engine and Metal Performance Shaders.

---

## 2. Information We Process & Where It Stays

### A. Voice Recordings & Audio Files
* **Local Processing:** When you record a voice reflection, your audio stream is processed locally on your iPhone using on-device neural models (WhisperKit).
* **Storage & Encryption:** Voice recordings are saved directly within the app's sandboxed local container and indexed in a secure SQLite database. 
* **User Control & Deletion:** You can delete any recording at any time. Deleting a reflection permanently erases the physical audio file and its database record from your device immediately.

### B. Transcripts & Cognitive Lenses
* **Local Analysis:** Transcripts, cognitive reframes (such as CBT, Stoic, Somatic, and Meaning lenses), emotional themes, and weekly mind reviews are computed entirely on-device by local inference engines.
* **No Third-Party AI Sharing:** Your thoughts are never uploaded to OpenAI, Google, Anthropic, or any third-party cloud AI APIs.

### C. Biometrics & Vault Protection
* If enabled, KnowYourself uses Apple's LocalAuthentication framework (Face ID, Touch ID, or device passcode) to lock your journal vault.
* Biometric authentication is handled strictly by Apple's Secure Enclave. The app never receives, stores, or transmits your biometric data.

### D. Subscriptions & In-App Purchases
* All purchases, trials, and subscription entitlements are processed directly through Apple's **StoreKit 2** framework.
* Transaction verification is validated against Apple’s cryptographic App Store receipts directly on your device. We do not maintain any external payment databases.

---

## 3. Apple Privacy Manifest (App Store Review Guideline 5.1.1)

In compliance with Apple's Privacy Manifest requirements, KnowYourself declares:
* **Tracking:** False (`NSPrivacyTracking = NO`). We do not track you across apps or websites.
* **Data Collected:** None (`NSPrivacyCollectedDataTypes = []`). No user data is collected or transmitted off-device.
* **Required Reason APIs:**
  * `NSPrivacyAccessedAPICategoryUserDefaults` (Reason `CA92.1`): Used solely to persist local app preferences, such as selected transcription language, biometric auto-lock timeout, and silence detection settings.
  * `NSPrivacyAccessedAPICategoryFileTimestamp` (Reason `C617.1`): Used solely to manage local audio file retention and synchronization within the app's private sandbox.

---

## 4. Backups and Data Portability

* **Local Export:** You retain 100% ownership of your journal entries.
* **iCloud Backups:** If you have enabled standard iOS iCloud Device Backups, your local sandbox data may be included in your encrypted personal iCloud backup according to your Apple ID settings. You can manage or exclude app data at any time via iOS Settings > [Your Name] > iCloud.

---

## 5. Health & Clinical Disclaimer

KnowYourself is designed as a mindful self-reflection tool and cognitive journaling companion. **It does not provide medical, psychiatric, or psychological diagnosis, advice, or treatment.** If you are experiencing acute psychological distress or a mental health crisis, please consult a qualified healthcare professional or contact emergency services in your region.

---

## 6. Children’s Privacy

KnowYourself does not knowingly collect or solicit any personal information from children under the age of 13. Because all data remains locally on the user's device, no personal data is collected from any user regardless of age.

---

## 7. Changes to This Policy

We may update this Privacy Policy from time to time to reflect product enhancements or evolving platform guidelines. Any changes will be posted in this document with an updated revision date.

---

## 8. Contact Us

If you have any questions or feedback regarding this Privacy Policy or the security of KnowYourself, please reach out via:
* **Repository:** [https://github.com/asheok/KnowYourself](https://github.com/asheok/KnowYourself)
* **Email:** aksheok1@gmail.com
