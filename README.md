# 🔐 Incident Simulations – SOC Analyst Simulation

This is a work-in-progress cybersecurity project that simulates a real SOC (Security Operations Center) alert pipeline with realistic, multi-stage attack scenarios.

## 🚧 Current Goals

- Redesigning UI and alert workflow from scratch
- Rebuilding Gemini-based alert and metadata generator
- Setting up clean alert storage (Firestore or local JSON)
- Simplifying architecture for stability and expandability

## 💡 Features (Planned)

- Multi-step alert generation: Recon → Access → Movement → Exfil
- AI-generated metadata (email bodies, console logs, filenames, etc.)
- “More Details” view for each alert
- Alert filtering (severity, category, resolved)
- Real-world style analyst workflow

## 🧠 Tech Stack

- Vanilla JS, HTML, CSS (no framework)
- Gemini AI for content generation
- Firebase for alert storage
- GitHub for project management

## 🖼️ UI Preview (WIP)

![Dashboard Preview](./screenshots/dashboard-preview.png)

## 🔄 Status

- 🟨 Planning & restructure
- ⏳ UI rebuild
- 🔜 Gemini prompt tuning
