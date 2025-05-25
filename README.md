# 🛡️ Phishing Simulation Campaign - Internship Task

This repository documents a **phishing simulation campaign** executed by **Tobechukwu** as part of a cybersecurity internship. The objective was to simulate phishing emails, monitor user interactions, and assess awareness in a controlled environment.

---

## 🎯 Objective

- Test awareness and phishing response in a simulated environment.
- Create phishing templates and landing pages.
- Track engagement and analyze results.
- Recommend improvements to training programs.

---

## 🧰 Tools Used

- [GoPhish](https://getgophish.com) – Phishing simulation framework.
- [Mailtrap.io](https://mailtrap.io) – Email sandbox for SMTP testing.
- **SQLite3** – To query the GoPhish database if needed.
- **Kali Linux VM** – Used for campaign execution.
- **GitHub** – Project documentation and report versioning.

---

## ⚙️ Setup Overview

1. **Downloaded GoPhish** and ran it inside Kali Linux.
2. **Configured Mailtrap** as the SMTP sending profile in GoPhish.
3. **Created a Landing Page** mimicking a fake login portal.
4. **Built an Email Template** warning about a password expiry.
5. **Added Dummy Recipients** using Mailtrap inbox addresses.
6. **Launched the Campaign** and tracked results.

---

## 📝 Email Template

```html
<p>Dear Team,</p>
<p>Your account password is set to expire in 24 hours.</p>
<p>Please click the secure link below to verify your credentials:</p>
<p><a href="{{.URL}}">Verify Account</a></p>
<p>Best regards,<br>IT Helpdesk<br>SecureCorp</p>
```

---

## 🌐 Landing Page

A login-themed landing page titled “SecureCorp Portal” was created. When users clicked the phishing link, they were redirected to this fake login page.

---

## 👥 Target Group

Test email addresses from Mailtrap were used to simulate employees. No real users were targeted.

---

## 📊 Campaign Metrics

| Metric             | Value |
|--------------------|-------|
| Emails Sent        | 5     |
| Emails Opened      | 2     |
| Links Clicked      | 1     |
| Credentials Captured | 0   |

> **Note:** Mailtrap does not simulate actual clicks, so link tracking was limited.

---

## 📘 Key Takeaways

- Successfully installed and configured GoPhish.
- Used Mailtrap safely to simulate email delivery.
- Designed and deployed phishing email and landing page.
- Observed basic metrics and understood campaign tracking.

---

## 📁 Project Files

- `Phishing Simulation Campaign Report.pdf` — Final report file will attached to this repo

---

## ✅ Recommendations

- Perform real-user testing in a closed environment for better realism.
- Include phishing awareness in employee onboarding.
- Run periodic phishing simulations to reinforce training.
- Expand templates to include other social engineering styles.

---

## 👨🏽‍💻 Author Info

**Name:** Tobechukwu Nicholas

**Role:** Cybersecurity Intern  
**Task:** Social Engineering & Phishing Simulation  
**Date:** May 2025
