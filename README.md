# 🛡️ ScamShield

An open-source, privacy-first citizen defense platform built to protect non-tech-savvy users from regional phishing, panic threats, and digital fraud.

Built and deployed during the **Hacktoberfest Hack Day (Delhi NCR)** at **Microsoft Office, Gurugram**.

🔗 **Live Demo:** [https://adivyapandey.github.io/ScamShield/](https://adivyapandey.github.io/ScamShield/)

---

## 🚨 The Problem

Cyber scammers frequently target everyday citizens across Tier-2 and Tier-3 regions using local languages and fear-inducing tactics (fake electricity disconnection notices, frozen bank accounts, unauthorized KYC updates, pension cutoffs). 

Standard caller-ID and spam tools often stop at labeling a message as "spam" without giving vulnerable individuals clear, immediate steps on what action to take.

---

## ✨ Key Features

- **Multimodal Threat Ingestion:** Analyzes suspicious raw text, SMS screenshots, phishing URLs, and regional voice queries.
- **Client-Side Privacy (In-Browser OCR):** Leverages **Tesseract.js** directly inside the browser, ensuring sensitive personal screenshots never leave the client's local device.
- **Sub-Second Threat Intelligence:** Powered by open-weight LLMs via **Groq LPUs**, evaluating scam probability with a transparent **0–100 Risk Score** and immediate advisories in under 0.5 seconds.
- **Actionable Citizen Defense:** Automatically generates a pre-formatted legal complaint draft ready for submission on **cybercrime.gov.in**, coupled with a direct dialer for the **1930 National Cyber Helpline**.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Lightweight, zero-bloat architecture)
- **Local OCR:** Tesseract.js
- **AI Inference:** Open-weight LLMs hosted on Groq LPU
- **Deployment:** GitHub Pages

---

## 🚀 Future Roadmap

- Background OS-level notification and SMS interception with automated severity banners.
- Offline-first local risk parsing for minimal network dependencies.
- Expanded native dialect coverage for regional audio inputs.

---

## 📄 License

This project is open-source under the MIT License.
