# EcoGrid-AI
# ⚡ EcoGrid AI
**Powering smart urban micro-grids, one autonomous routing decision at a time.**

Built for the **Decoding Data Science — Building Agentic AI Application Challenge** (No-Code / Low-Code Track).

---

## 🔗 Quick Links
- **Live App Demo (Lovable):** `https://ecogrid-sallysohieb.lovable.app`
- **Progress Workbook:** Included in this repository 

---

## 📖 Project Overview
**EcoGrid AI** is an autonomous micro-grid load balancer designed for smart urban energy management. It evaluates real-time solar generation, battery reserve levels, and community electricity demand to recommend optimal load-routing actions—minimizing grid strain, reducing peak energy costs, and lowering carbon emissions.

### Core Capabilities
- **Real-Time Telemetry Simulation:** Interactive sliders for Solar Generation (`0–500 kW`), Community Demand (`0–500 kW`), and Battery Reserve (`0–100%`).
- **Autonomous Decision Routing:** LLM-driven logic dynamically routes power between *Direct Solar Consumption*, *Battery Charge/Discharge*, *Grid Draw*, and *Emergency Load Shedding*.
- **One-Click Edge-Case Presets:** Instant testing modes for *Peak Noon Solar*, *Evening Demand Spike*, and *Grid Emergency / Blackout Risk*.
- **Security & Input Guardrails:** Strict numeric boundary enforcement, input validation, and high-contrast fallback warning banners for extreme grid conditions.
- **Operator Feedback & Audit Logs:** Built-in Helpful/Not Helpful rating loop and one-click JSON/CSV decision log exports.

---

## 🛠️ Tech Stack & Architecture
- **Frontend & Workflow Orchestration:** Lovable (No-Code AI Application Builder)
- **Decision Engine:** Structured Prompt Engineering & JSON Schema Output Enforcement
- **Security & Guardrails:** Input range clamping, fallback edge-case handling, zero-PII synthetic telemetry

---

## 🧪 Evaluation & Testing Summary
The application was evaluated across normal and extreme micro-grid scenarios:
1. **Peak Noon Solar (`420 kW` Solar | `180 kW` Demand | `85%` Battery):** Routes excess energy to storage/export and displays positive carbon offset metrics.
2. **Evening Demand Spike (`20 kW` Solar | `410 kW` Demand | `35%` Battery):** Prioritizes controlled battery discharge before drawing from the main utility grid.
3. **Grid Emergency (`0 kW` Solar | `450 kW` Demand | `8%` Battery):** Triggers the Critical Grid Alert banner and activates load-shedding fallback protocols.

---

## 📂 Repository Contents
- `README.md` — Project overview, architecture, and live demo instructions.
- `DDS_Building_AI_Challenge_Progress_Workbook.pdf` — Complete daily development logs, checklists, and evaluation notes.
- `screenshots/` — Visual evidence of the UI, edge-case alerts, and export logs.

---

## 👤 Author
- **Name:** Sally Sohieb
- **Challenge:** Decoding Data Science — Building Agentic AI Application Challenge
