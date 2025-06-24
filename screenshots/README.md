# 🖼️ SOC Simulation – UI Screenshots

This folder contains user interface screenshots from my fully custom-built SOC (Security Operations Center) simulation project. Each image reflects a different core feature of the simulation, built to model real-world alert management, threat intelligence, log analysis, and analyst workflow.

---

## 📊 Dashboard

**File:** `Screenshot 2025-06-24 at 15-44-28 SOC Simulator - Final.png`  
Shows a high-level summary of:
- Total alerts in the past 24h
- Open cases
- Alerts by severity (donut chart)
- Live threat picture with top attacker and target IPs

---

## 🚨 Alerts Feed

**File:** `Screenshot 2025-06-24 at 15-44-36 SOC Simulator - Final.png`  
Displays real-time alerts with:
- Severity labels (Critical, High, Low, etc.)
- Source and destination IPs
- Descriptions of attack types like SQL Injection, Malware, Port Scans

---

## 🔍 Log Search

**File:** `Screenshot 2025-06-24 at 15-44-54 SOC Simulator - Final.png`  
This interface allows users to search logs tied to a specific alert ID or keyword.  
Also shows correlated logs and detailed metadata such as data exfiltration indicators and user activity.

---

## 🧠 Threat Intelligence

**File:** `Screenshot 2025-06-24 at 15-45-00 SOC Simulator - Final.png`  
Built-in threat intel lookup tool that:
- Analyzes IP addresses
- Returns a risk score
- Displays known tags, history, and location based on threat feed data

---

## 👤 Analyst Profile

**File:** `Screenshot 2025-06-24 at 15-45-06 SOC Simulator - Final.png`  
Displays analyst progress with:
- Leveling system
- XP tracking
- Unlockable achievements for SOC performance (e.g., detecting false positives, escalating alerts)

---

## ⚙️ Settings

**File:** `Screenshot 2025-06-24 at 15-45-13 SOC Simulator - Final.png`  
UI for controlling alert feed speed and saving/loading simulation progress.

---

## 🔧 Technical Note

This entire UI is built using HTML, CSS, and JavaScript (no frameworks), with Gemini AI generating alert content and metadata. The simulation mimics a real SOC workflow and is fully customizable for training or demonstration purposes.


