# WhoDAT

This project is a lightweight browser-based information collector that gathers client-side data such as IP details, device specifications, browser metadata, and cookies. It packages the data into a ZIP file and sends it via a webhook.

> ⚠️ **Disclaimer:** This project is intended for **educational** and **ethical** use only. Do **not** deploy or use this script on websites without clear user consent. Violating privacy laws or terms of service can result in legal consequences.

---

## 🚀 Features

- 📡 **IP Information** — Uses `ipinfo.io` to gather public IP, ISP, location, and VPN detection.
- 💻 **Browser & Device Data** — Captures browser name, version, OS, user agent, device type, and screen resolution.
- 🍪 **Cookie Collection** — Retrieves browser cookies (if available).
- 📦 **ZIP Compression** — Organizes and compresses the collected data using `JSZip`.
- 📤 **Webhook Delivery** — Sends the ZIP file to a specified webhook (e.g., Discord).

---

## 📌 Technologies Used

- HTML5  
- JavaScript  
- [JSZip](https://stuk.github.io/jszip/)  
- [ipinfo.io](https://ipinfo.io/)  
- Fetch API

---

## ⚙️ Setup & Usage

### 1. Clone the Repository

```bash
[git clone https://github.com/yourusername/web-info-collector.git
cd web-info-collector](https://github.com/SavJas/WhoDatInfoGrabber.git)
```

### 2. Replace the Webhook

Open the HTML file and find this line:
```
fetch("webhook_url", {
```
Replace "webhook_url" with your actual webhook URL (such as a Discord webhook).


### 🚀 Deploy to the Web
You can host this project for free using platforms like Vercel or Netlify.

# ❗ Ethical Use Reminder

#### This tool is intended for:

- ✅ Penetration testing (with proper permission)

- ✅ Educational demonstrations

- ✅ Browser fingerprinting research

**Do not use this tool for malicious purposes or without clear, informed consent from users.**

### 📄 License
**This project is open-source under the MIT License.**
