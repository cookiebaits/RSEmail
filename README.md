# 🛡️ RuinScam Email Phishing Simulator

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Launch%20App-0078d4?style=for-the-badge&logo=mail)](https://cookiebaits.github.io/RSEmail/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/cookiebaits/RSEmail)

An interactive, browser-based cybersecurity awareness tool designed to train users on identifying modern email phishing techniques, deceptive domain spoofing, malicious attachments, and social engineering lures. Featuring a realistic webmail interface, **RuinScam Email Phishing Simulator** runs completely client-side while persisting individual user training states locally.

---

## 🚀 Live Access

Access the live web application directly in your browser:  
**👉 [https://cookiebaits.github.io/RSEmail/](https://cookiebaits.github.io/RSEmail/)**

---

## ✨ Key Features

* **25 Email Batch Engine (40/60 Split)**: Generates 25 randomized emails per weekly cycle (10 phishing threats and 15 legitimate communications) in an unpredictable order.
* **Automated Daily Phishing Influx**: Automatically delivers **3 new phishing emails every 24 hours** to simulate an active, ongoing corporate inbox threat landscape.
* **Isolated Browser Caching (`localStorage`)**: Automatically caches folder state, read history, and current selections per browser. Multiple users on the same device or site remain completely isolated.
* **Weekly Cleanup & Indefinite Performance Tracking**: Advancing the 7-day cycle clears emails marked as *Safe* or *Junk/Spam*, while retaining **Training Performance stats (Caught, False Positives, Detection Accuracy) indefinitely**.
* **Detailed Educational Feedback & Red Flag Analysis**: Replaces generic pop-ups with an interactive modal analysis upon email classification. If a user makes a mistake, the app highlights the exact technical red flags missed or explains why a legitimate email was safe.
* **Realistic PDF Document Preview Modal**: Built-in PDF reader for inspecting invoice line items, payment status indicators, vendor details, and destination links before taking action.
* **Hover Link URL Inspection**: Live status bar at the bottom of the reading pane previews raw destination URLs on link hover, revealing domain mismatches and unencrypted HTTP targets.
* **Onboarding & Instruction System**: Modal training guide available on initial launch or via top menu, explaining how to spot typosquatting, comboglyphs, and homographs.

---

## 🔍 Phishing Techniques & Red Flags Simulated

| Technique / Lure | Technical Implementation |
| :--- | :--- |
| **Typosquatting** | Spoofed domains with subtle misspellings (`quickbo0ks`, `docusgn`, `amzon`). |
| **Homographs** | Visual character swaps, such as replacing lowercase `l` with capital `I` (`paypaI`). |
| **Comboglyphs** | Combining characters to mimic others, like `r` + `n` to look like `m` (`rnicro`). |
| **Deceptive Hyperlinks** | Mismatched anchor text where visible link text differs from the actual `href` target. |
| **Artificial Urgency** | Short deadline windows (e.g., 2-hour password expiration notices, 15% late fees). |
| **Malicious PDF Invoices** | Multi-item receipt attachments with fake billing totals and unverified checkout links. |
| **Authority & Fear Lures** | Executive wire transfer authorizations, foreign sign-in alerts, and direct deposit updates. |

---

## 🛠️ Local Development & Deployment

### Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/cookiebaits/RSEmail.git](https://github.com/cookiebaits/RSEmail.git)
