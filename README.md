# 🧩 Incident Simulations – SOC Analyst Dashboard Project

This is my capstone cybersecurity simulation project, where I replicate real-world incident workflows in a simulated Security Operations Center (SOC) dashboard.

## 🎯 Goal

Build and simulate realistic attack scenarios and generate alerts for training, analysis, and automation. The app mimics real SOC platforms like Splunk or Microsoft Sentinel.

## 🛠️ Features

- Gemini AI-powered alert generation
- Multi-step attack scenarios (Recon → Access → Lateral Movement → Exfil)
- Custom UI for reviewing alerts
- Firestore integration to store alerts and metadata
- Alert severity, category, source IP, and timestamps
- "More Details" view pulls AI-generated extra metadata

## 📁 Structure

- `scenarios/` – Markdown breakdowns of each attack path
- `alerts/` – AI-generated alert data (JSON)
- `metadata/` – Extra AI-generated context per alert
- `firestore/` – Database schema and test cases
- `tools/` – Scripts used to simulate attacks or generate logs
- `api/` – Gemini prompt design and prompt structure
- `screenshots/` – Visual demos of the SOC UI or app

## 🔧 Technologies

- HTML, CSS, JavaScript (Frontend)
- Gemini AI (Alert + Metadata)
- Firebase (Firestore DB)
- GitHub Pages (Optional Deployment)

## 📸 Demo

![SOC Preview](./screenshots/soc-dashboard-sample.png)

## 📌 Status

- 🔄 Core alert generation working
- ✅ Metadata integration done
- ⏳ UI final polish in progress

