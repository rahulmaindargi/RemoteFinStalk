# Privacy Policy

**Last updated:** 29-12-2025

**Introduction**
This Privacy Policy describes how **FinStalk** ("we", "our", or "the App") collects, uses, and protects your information. The App is developed by **Rahul Vivek Maindargi** as a standalone, offline-first tool for personal expense management.

We are committed to the principle that **your financial data belongs to you**. We do not own, sell, or view your personal data.

### 1. SMS Permission & Data Usage
To function as an automated expense tracker, the App requests the `READ_SMS` permission.

* **Why we need it:** In India, financial transaction alerts are primarily delivered via SMS. The App uses this permission to automatically parse incoming SMS messages from banks and financial institutions to create expense entries.
* **How it works:**
    * The App scans your SMS inbox **locally on your device**.
    * It uses strict pattern matching (Regex) to identify transaction messages (e.g., "Debited", "Credited", "UPI").
    * **Personal SMS messages are ignored** and are never stored in our database.
* **Data Safety:** Your raw SMS data and the parsed transaction data **never leave your device** to any server owned by the developer.

### 2. Internet Permission
The App requests internet access (`android.permission.INTERNET`) strictly for the following limited purposes:
1.  **Regex Updates:** To fetch updated SMS parsing definitions from the developer's public GitHub repository (`rahulmaindargi/RemoteFinStalk`). This ensures the app can recognize new bank SMS formats without a full app update.
2.  **User-Initiated Backup:** To allow you to backup your data to your own **Google Drive**. This action is manually triggered by you.

**No background analytics or tracking data is sent to the developer.**

### 3. Data Storage and Retention
* **Local Storage:** All your data (expenses, categories, budget limits) is stored in a secure local database on your smartphone.
* **No Remote Server:** The developer does not operate a backend server to store user data. If you uninstall the App without a backup, your data will be permanently deleted.

### 4. Third-Party Services
* **Google Drive:** If you choose to use the Backup/Restore feature, the App interacts with Google Drive APIs. This data is subject to Google's Privacy Policy and is stored in your personal cloud account.
* **Email (Feedback):** If you choose to report an unrecognized SMS format, the App will open your default Email client with the SMS text pre-filled. You have full control to edit or cancel this email before sending.

### 5. Changes to This Policy
We may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes.

### 6. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at **finstalk.app@gmail.com**.