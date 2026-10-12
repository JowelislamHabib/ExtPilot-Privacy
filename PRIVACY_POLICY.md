# Privacy Policy for ExtPilot

**Effective Date:** October 12, 2026  
**Last Updated:** October 12, 2026

ExtPilot ("we", "our", or "the extension") is developed by Jowel Islam Habib. We are committed to protecting your privacy. This Privacy Policy explains our practices regarding data collection, usage, and disclosure when you use ExtPilot.

---

### 1. Overview & Core Philosophy
ExtPilot is designed from the ground up with **privacy-by-default** and **local-first** principles:
- **Zero Data Collection:** We do not collect, transmit, store, sell, or share any personal data, browsing history, or user information.
- **100% Offline & Local Execution:** All rules, preferences, domain checks, and extension state toggles are processed entirely on your local machine using the Chrome Extension APIs.
- **No Third-Party Trackers or Analytics:** There are no analytics SDKs, trackers, cookies, or remote logging services embedded in ExtPilot.

---

### 2. Permissions & How They Are Used
ExtPilot requests the minimum permissions necessary to fulfill its single core purpose—managing your Chrome extensions based on website domains.

| Permission | Purpose | Data Handled |
| :--- | :--- | :--- |
| `management` | Allows ExtPilot to read the list of installed extensions and enable/disable them according to your custom rules. | Extension IDs, names, and enabled states. Never transmitted anywhere. |
| `tabs` | Allows ExtPilot to inspect the active tab's domain name when you switch tabs or navigate to a new site, in order to trigger your configured rules. | Domain hostname of the active tab. Evaluated entirely in-memory and never logged or sent to any server. |
| `storage` | Stores your custom domain rules, whitelist/blacklist configurations, and settings locally using `chrome.storage.local`. | Stored exclusively on your local device. |

---

### 3. Remote Code & External Communication
ExtPilot strictly complies with Google Chrome Web Store policies:
- It does **not** load or execute remote code (no `eval`, no remote scripts, no remote CSS).
- It does **not** make external network requests (`fetch` or `XMLHttpRequest`).

---

### 4. Children’s Privacy
ExtPilot does not collect any data from anyone, including children under the age of 13.

---

### 5. Changes to This Policy
If we update this Privacy Policy, the updated version will be posted in this repository with a revised "Last Updated" date.

---

### 6. Contact
If you have any questions or concerns regarding this Privacy Policy or ExtPilot, please contact:
- **Developer:** Jowel Islam Habib
- **GitHub:** [https://github.com/JowelislamHabib/ExtPilot-Chrome-Extension](https://github.com/JowelislamHabib/ExtPilot-Chrome-Extension)
- **Website:** [https://jowel.bintofajjal.com/](https://jowel.bintofajjal.com/)
