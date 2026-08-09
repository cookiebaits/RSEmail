# 🛡️ RuinScam Email Phishing Simulator

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Launch%20App-0078d4?style=for-the-badge&logo=mail)](https://cookiebaits.github.io/RSEmail/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/cookiebaits/RSEmail)

A browser-based, interactive security tool built to train users on identifying phishing techniques, false links, malicious attachments, and social engineering tactics. Designed with a familiar enterprise webmail GUI interface, the simulator generates randomized weekly email batches to test security awareness without requiring backend infrastructure or server setups.

---

## 🚀 Live Access

Access the live web application directly in your browser:  
**👉 [https://cookiebaits.github.io/RSEmail/](https://cookiebaits.github.io/RSEmail/)**

---

## ✨ Features

* **Modern Webmail GUI**: Styled after clean webmail interfaces, complete with dynamic navigation, a three-pane reading view, action toolbars, and live folder counters.
* **40% Phishing / 60% Legitimate Distribution**: Weighted random generation engine that ensures unpredictable email delivery every cycle.
* **7-Day Dynamic Cycle Engine**: Clears old emails and delivers new randomized batches every simulated week (with manual cycle advancement controls).
* **Hover Link URL Inspection**: Built-in browser status bar displays raw destination URLs when hovering over links to help identify deceptive domains.
* **Document Attachment Previews**: Interactive preview modals allowing users to safely inspect fake invoices, receipt summaries, and shipping manifests before deeming emails safe.
* **Actionable Reporting Workflows**:
  * **🚩 Report Phishing**: Routes suspect emails to the Junk/Spam folder and logs performance stats.
  * **✅ Mark as Safe**: Verifies emails and moves them to the Safe folder.
  * **🗑️ Delete**: Removes temporary inbox clutter.
* **Real-Time Performance Tracking**: Live analytics panel calculating caught phishing attempts, false positives, and overall user accuracy percentages.
* **100% Serverless & Client-Side**: Built with pure HTML, CSS, and vanilla JavaScript—runs entirely in the browser with zero external dependencies.

---

## 🔍 Phishing Scenarios Included

| Scenario Type | Common Indicators / Red Flags |
| :--- | :--- |
| **Overdue Invoices & Billing** | Misspelled sender domains, urgent penalty threats, mismatched payment gateway URLs |
| **Account Security Alerts** | Typosquatted login domains, generic greetings, suspicious sign-in locations |
| **IT & Password Expirations** | Unofficial external domain addresses, artificial urgency to prevent account lockout |
| **Delivery Failure Notices** | Mandatory document attachment preview required, immediate fee demands for redelivery |

---

## 🛠️ Local Development & Deployment

### Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/cookiebaits/RSEmail.git](https://github.com/cookiebaits/RSEmail.git)
