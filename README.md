# UniCare+ 

This repository contains the backend architecture and AI integration
for **UniCare+**, an accessibility-first healthcare application.

The frontend UI is built using Base44.
This repository demonstrates how the backend and AI services
connect to the UI for a hackathon MVP.

---

## 🚀 Features Covered

- Speech Therapy analysis (guidance-only)
- Occupational Therapy (Kids & Adults) movement feedback
- Hearing module support (ABR info, PTA, Clinical PTA)
- Multilingual & Text-to-Speech ready architecture
- Offline-first design with online sync

---

## 🧠 AI Usage (Non-Diagnostic)

This app uses AI **only for guidance**, not medical judgment.

### Speech Therapy
- Pronunciation and clarity feedback
- Rule-based scoring (no diagnosis)

### Occupational Therapy (OT)
- Body posture & movement analysis
- Angle and stability comparison
- Feedback only:
  - 🟢 Excellent posture
  - 🟡 Slow down
  - 🔴 Try again with support

### Hearing Module
- ABR: Information only
- PTA: Tap-based home guidance
- Clinical PTA: Hospital booking support

---

## 🌐 Offline & Online Working

- Exercises and videos work offline
- Data is stored locally on device
- Syncs automatically when internet is available
- Suitable for low-connectivity regions

---

## 🛠 Tech Stack (Planned / MVP)

- Node.js + Express (backend)
- REST APIs for AI integration
- MediaPipe (planned) for pose detection
- Rule-based engines for feedback
- No cloud dependency required for core usage

---

## ⚠️ Disclaimer

UniCare+ provides **assistive guidance only**.
It does NOT replace professional diagnosis or therapy.
Final medical authority remains with certified professionals.

---

## 📌 Hackathon Note

This repository focuses on:
- Architecture
- Feasibility
- AI integration points

It is intentionally lightweight and modular.
