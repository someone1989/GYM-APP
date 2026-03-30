<p align="center">
  <img src="https://img.shields.io/badge/🏔️_GymClimb-Tracker-00d2ff?style=for-the-badge&labelColor=0a0a14" alt="GymClimb"/>
  <br/><br/>
  <img src="https://img.shields.io/badge/version-4.0-51cf66?style=flat-square&labelColor=111118" alt="Version"/>
  <img src="https://img.shields.io/badge/PWA-ready-ffd43b?style=flat-square&labelColor=111118" alt="PWA"/>
  <img src="https://img.shields.io/badge/offline-100%25-00d2ff?style=flat-square&labelColor=111118" alt="Offline"/>
  <img src="https://img.shields.io/badge/Garmin_Fenix_7X-integrated-748ffc?style=flat-square&labelColor=111118" alt="Garmin"/>
</p>

<p align="center">
  <b>Standalone workout + climbing + hiking tracker</b><br/>
  Optimized for iPhone · Garmin Fenix 7X integration · Zero server dependency
</p>

---

## ✨ Features

### 🏋️ Training
- **7-day program** (Mass + Climbing) with fully customizable exercises
- **Set-by-set tracking** — weight, reps, RPE, previous week comparison
- **1RM calculator** (Epley formula) with automatic PR detection 🏆
- **Volume tracking** — per session and weekly totals in tons
- **Program editor** — add, remove exercises per day in Settings

### 🧗 Climbing
- **Route log** — bouldering grades V0–V12, sport grades 4a–8a
- **Send status** — Flash ⚡ / Redpoint 🔴 / Project 🔧
- **Bouldering pyramid** — visual progression chart
- **Hangboard tracker** — grip type, added weight, hang time, edge size

### 🥾 Hiking
- **Trail log** — name, distance, elevation gain, duration
- **Difficulty rating** — Easy / Moderate / Hard / Expert

### ⌚ Garmin Fenix 7X Integration
- **Morning check-in** — 4 numbers from your watch glance:
  - 🎯 Training Readiness · 🔋 Body Battery · 😴 Sleep Score · ⏳ Recovery Time
- **Post-workout data** — HR, calories, Training Effect, Load (EPOC)
- **Smart recovery alerts** — warns when readiness or battery are low
- **Trend charts** — track recovery metrics over weeks

### 📊 Dashboard
- **SVG charts** — readiness trends, lift progression, weekly volume
- **PR Wall** — ranked by estimated 1RM 🥇🥈🥉
- **Dismissible reminders** — with badge count on nav bar

### 📏 Body Tracking
- **BMI** — auto-calculated from height + weight with category
- **Measurements** — waist, chest, arms, body fat %
- **Weekly progress** — all metrics tracked over time

### 📱 App Features
- **PWA** — install on home screen, works like native app
- **100% offline** — no server, no account, no signup
- **Export / Import** — backup & transfer data as JSON
- **Dark theme** — designed for gym & outdoor use
- **iPhone optimized** — safe areas, smooth scrolling, no input zoom

---

## 🚀 Quick Start

### Deploy to GitHub Pages

```
1. Create new repository on GitHub
2. Upload index.html + README.md
3. Settings → Pages → main branch → Save
4. Wait 1 min → live at https://USERNAME.github.io/REPO/
```

### Install on iPhone

```
1. Open the URL in Safari
2. Tap Share button (□↑)
3. Tap "Add to Home Screen"
4. Done 🏔️
```

---

## 💾 Where is my data?

| What | Where | Visible to |
|------|-------|------------|
| App code | GitHub Pages | Public |
| Workout data | localStorage on YOUR device | Only you |
| Garmin entries | localStorage on YOUR device | Only you |
| Body measurements | localStorage on YOUR device | Only you |

> **Nothing is sent to any server.** All data stays on your phone.

**Backup:** Settings → 📤 Export → saves `.json` file
**Restore:** Settings → 📥 Import → loads `.json` file
**Transfer:** Send the JSON file to another device via AirDrop/email

---

## 🛠️ Tech Stack

Single HTML file. No build step. No backend. No dependencies to install.

| Library | CDN | Purpose |
|---------|-----|---------|
| React 18 | cdnjs.cloudflare.com | UI framework |
| Babel Standalone | cdnjs.cloudflare.com | JSX in browser |
| DM Sans + Space Mono | Google Fonts | Typography |
| Charts | Built-in SVG | Zero dependency |

---

<p align="center">
  <sub>Built with ❤️ for gym rats who also climb mountains</sub>
</p>
