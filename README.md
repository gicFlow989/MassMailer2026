# Mass Mailer Pro - Bulk Email Sender & SMTP Rotator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Technology](https://img.shields.io/badge/Tech-HTML5%20%7C%20Tailwind%20%7C%20JS-blue)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Status](https://img.shields.io/badge/Status-Active-success)]()

**Mass Mailer Pro** is a powerful, open-source **bulk email sender** and **SMTP rotation tool** designed for high-volume email marketing campaigns, newsletters, and cold outreach. Built with modern web technologies, this lightweight **mass mailing software** allows you to send unlimited emails using multiple SMTP servers to ensure high deliverability and avoid spam folders.

---

## Key Features

### 🔄 Advanced SMTP Management & Rotation
*   **Multi-SMTP Support:** Add unlimited **SMTP servers** (Gmail, Outlook, AWS SES, SendGrid, Zoho, etc.).
*   **Load Balancing:** The **SMTP rotator** automatically distributes traffic across all configured servers to prevent IP blacklisting.
*   **Secure Connection:** Supports TLS/SSL and custom ports (587, 465, 25).

### Anti-Spam & Deliverability Tools
*   **Subject Randomization:** Input multiple subject lines; the tool shuffles them for every email to bypass spam filters that flag identical subject lines.
*   **Smart Delays:** Configure minimum and maximum time delays (in seconds) between sends to mimic human behavior.
*   **Content Spinning:** Rotate through different server configurations automatically.

### 🎨 HTML Content & Personalization
*   **Rich HTML Support:** Send professional HTML newsletters and marketing templates.
*   **Dynamic Tags:** Personalize every email with recipient details to boost open rates.
    *   `{email}` - Inserts recipient email.
    *   `{name}` - Auto-extracts name from email address.
    *   `{date}` & `{time}` - Inserts current timestamp.

### 📊 Real-Time Campaign Dashboard
*   **Live Progress Bar:** Track sent, failed, and pending emails in real-time.
*   **Detailed Logs:** View success/error logs with timestamps for debugging connection issues.
*   **Browser-Based:** Runs entirely in your browser using local storage—no database or complex backend required.

---

## 📸 Screenshots & Interface

### 1. SMTP Server Configuration
Manage your mailing infrastructure. Add, remove, and test multiple SMTP connections easily.
![Mass Mailer SMTP Configuration - Bulk Email Server Setup](https://i.ibb.co/PZ1Xh2w1/Screenshot-2026-01-05-at-11-19-15.png)

### 2. Email Content Editor
Compose HTML emails and manage your bulk recipient lists (supports CSV style copy-paste).
![HTML Email Editor - Mass Mailer Content Management](https://i.ibb.co/NnFSsLYP/Screenshot-2026-01-05-at-11-19-09.png)

### 3. Campaign Randomizer
Configure anti-spam settings, subject line shuffling, and sending intervals.
![Email Randomizer - Anti-Spam Configuration](https://i.ibb.co/8LX6JDZX/Screenshot-2026-01-05-at-11-19-02.png)

### 4. Sending Dashboard
Watch your campaign execution with live logs and progress tracking.
![Bulk Email Sending Progress - Real Time Logs](https://i.ibb.co/Kcsfv2Rc/Screenshot-2026-01-05-at-11-18-52.png)

---

## 🛠️ Installation & Usage

This is a **client-side mass mailer** built as a Single Page Application (SPA).

1.  **Download:** Clone this repository or download the ZIP file.
2.  **Run:** Open `index.html` in any modern web browser (Chrome, Firefox, Edge).
3.  **Configure:**
    *   Go to the **SMTP Servers** tab and add your provider details.
    *   Go to **Email Content** to paste your leads and HTML body.
    *   Adjust settings in **Randomizer** for optimal delivery.
4.  **Launch:** Click **Start Campaign** in the Send tab.

*Note: No server installation (Node.js/PHP/Python) is required to run the interface.*

---

## 📋 Technical Specs

*   **Framework:** Vanilla JavaScript (ES6+)
*   **Styling:** Tailwind CSS (CDN)
*   **Storage:** HTML5 LocalStorage (Your SMTP credentials stay in your browser, never uploaded to a cloud).
*   **Responsiveness:** Fully responsive design for Desktop and Mobile management.

---

## 🔍 SEO Keywords
*Bulk Email Sender, Mass Mailer, SMTP Rotator, Free Email Marketing Tool, Send Unlimited Emails, HTML Newsletter Sender, Cold Email Software, Spam Checker, Email Blaster, Open Source Mailer, JavaScript SMTP Client.*

---

## ⚠️ Disclaimer

This tool is intended for **legitimate email marketing** (newsletters, opt-in lists, transactional emails) and educational purposes. The developers are not responsible for any misuse of this software for spamming (UCE). Please ensure you comply with CAN-SPAM Act, GDPR, and your SMTP provider's Terms of Service when sending mass emails.

---

[Report Bug](https://github.com/yourusername/repo/issues) | [Request Feature](https://github.com/yourusername/repo/issues)
