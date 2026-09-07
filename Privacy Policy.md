**Know Yourself** ("we", "our", or "us") is built on a fundamental principle: **Your mind belongs to you.**

This Privacy Policy explains how our Android application handles your data. Because Know Yourself is engineered as a 100% offline, zero-knowledge vault, our policy is incredibly simple: **We do not collect, store, transmit, or have access to any of your personal data, audio recordings, or journal entries.**

### **1\. Zero Data Collection & On-Device Processing**

Know Yourself is an entirely local application.

* **Audio & Transcriptions:** All voice recordings, speech-to-text transcriptions, and AI-generated insights are processed 100% on your physical device using local AI models.  
*   
* **No Cloud Servers:** We do not own, operate, or rent servers to process your data. Your data never leaves your device to be processed by us, OpenAI, Google, or any third-party AI provider.  
*   
* **No Telemetry:** We do not track your app usage, screen taps, or behavioral analytics.  
* 

### **2\. Permissions We Request and Why**

To function correctly, the app requires specific Android permissions. We only use these permissions locally:

* **Microphone (**RECORD\_AUDIO**):** Required to capture your voice journals. The audio is processed locally on your device's processor and is never streamed over the internet.  
*   
* **Biometrics (**USE\_BIOMETRIC**):** Required to lock your journal vault. Biometric authentication (fingerprint/face unlock) is handled securely by the Android OS. We do not access or store your biometric data.  
* 

### **3\. Encrypted Google Drive Backups (Optional)**

You may choose to enable automated cloud backups to prevent data loss. If you opt-in:

* The app connects directly to **your personal Google Drive** account via Google Sign-In.  
*   
* **Zero-Knowledge Encryption:** Before any data leaves your phone, your database and audio files are encrypted using military-grade AES-256-GCM cryptography.  
*   
* **App Data Folder:** Backups are stored in a hidden, app-specific folder in your Google Drive.  
*   
* **We Cannot Read Your Backups:** Because the encryption keys are derived on your device and never sent to us, we cannot decrypt, read, or access your backups under any circumstances.  
* 

### **4\. Crash Logs and Debugging**

We do not use automatic cloud-based crash reporting tools (like Firebase Crashlytics) that silently siphon device data.

* If the app crashes, an error log is generated and saved **locally** on your device.  
*   
* You have the option to manually export this text file and email it to us for debugging. You are entirely in control of whether this data is shared.  
* 

### **5\. Third-Party Libraries**

The app utilizes open-source and local libraries to function, including:

* **whisper.cpp & Google MediaPipe:** Used for on-device speech-to-text and AI summarization. All processing happens offline.  
*   
* **SQLCipher:** Used to encrypt the local SQLite database stored on your phone.  
* 

### **6\. Children's Privacy**

Our application does not knowingly collect any personal information from children under the age of 13\. Given the offline nature of the app, we do not collect information from users of any age.

### **7\. Changes to This Privacy Policy**

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date.

### **8\. Contact Us**

If you have any questions about this Privacy Policy or the security architecture of the app, please contact us at:  
**sh.akshay.797@gmail.com**