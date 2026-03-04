# 🛡️ ATTENDANCE GUARDIAN
### Predictive Attendance Intelligence for Poornima University Students

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Krishna-code7/ATTENDANCE)
![Language](https://img.shields.io/badge/Language-Vanilla%20JS-yellow)
![Status](https://img.shields.io/badge/Status-Beta%20v1.0-orange)

**ATTENDANCE GUARDIAN** is a specialized utility designed to bridge the gap between static attendance data and academic planning. While standard portals only show current status, this tool uses predictive logic to help students manage their schedules effectively.

---

## 🚀 The "Anti-TCS" Advantage
Standard portals (TCS iON) only show you where you are. This tool shows you where you're going:

* **Bunk Simulator:** A real-time engine that predicts your percentage after skipping $X$ classes.
* **Recovery Calculator:** Tells you exactly how many consecutive classes you must attend to hit the 75% safety mark.
* **Offline-First:** Engineered to work without internet after the initial load—perfect for quick checks in college labs.

---

## 🧠 Engineering Logic
The core of this project relies on two primary mathematical models:

1. **Bunk Impact Logic:**
   $$P_{new} = \frac{A}{T + B} \times 100$$
   *(Where A = Attended Classes, T = Total lasses, B = Planned Bunks)*

2. **The 75% Recovery Formula:**
   $$N = \lceil \frac{0.75T - A}{0.25} \rceil$$
   *(Calculating the minimum classes N required to stabilize attendance)*

---

## 🛠️ Development & Collaboration
I am currently opening this project for collaboration with seniors and batchmates.

**Current Roadmap:**
- [ ] **Automation:** Developing a scraper for direct TCS iON data synchronization.
- [ ] **Granularity:** Subject-wise credit weighting integration.
- [ ] **Mobile Native:** Compiling to an offline APK (In Progress).

---

## 👨‍💻 Developer
**Krishna Solanki** *B.Tech AI & Data Science | Poornima University* [Connect on LinkedIn](https://www.linkedin.com/in/krishna-solanki-355942367)
