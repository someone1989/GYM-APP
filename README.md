<h1 align="center">🏔️ GymClimb v6.0</h1>
<p align="center"><b>Gym · Climbing · Hiking · Running · Yoga · Smartwatch · Weather</b><br/><sub>One HTML file. No server. No signup. Your data stays on your phone.</sub></p>

---

## 🚀 Setup
1. Open GitHub Pages link in **Safari** (iOS) or **Chrome** (Android)
2. Tap **Share** → **Add to Home Screen**
3. Settings → name, city, smartwatch, language

## 🌐 Languages
🇬🇧 English · 🇭🇷 Hrvatski · 🇩🇪 Deutsch — Settings → Language

---

## 📱 All Features

### 🏋️ Training Program
- 7-day customizable split with day names translated (PON/UTO/SRI...)
- Set-by-set tracking: weight (kg), reps, RPE
- **↑↓ weight delta** – green/red badge vs last week
- 1RM calculator (Epley) + automatic PR detection 🏆
- ✓ Quick complete (per exercise or full day)
- ⏱ Rest timer (60/90/120/180s)
- Program editor in Settings

### 🧗 Climbing (Outdoor tab)
- Bouldering V0–V12 / Sport 4a–8a
- Flash ⚡ / Redpoint 🔴 / Project 🔧
- Location, duration (h+min), attempts, weather emoji, notes
- Tap → expand details → **✏️ Edit** or **🗑️ Delete**

### 🥾 Hiking (Outdoor tab)
- Trail name, distance (km), elevation (m), duration (min)
- Difficulty: Easy / Moderate / Hard / Expert
- Weather conditions + temperature
- Tap → expand → **✏️ Edit** or **🗑️ Delete**

### 🏃 Running (Outdoor tab) — *NEW*
- Route name, distance (km), duration (min)
- **Auto pace calculation** (e.g. 5'30" /km)
- Average heart rate (bpm)
- Feel rating: 😤 😐 🙂 😊 🔥
- Tap → expand → **✏️ Edit** or **🗑️ Delete**

### 🧘 Yoga (Outdoor tab) — *NEW*
- 7 styles: Vinyasa, Hatha, Yin, Power, Restorative, Ashtanga, Mobility
- Duration (min)
- Focus: Full body / Flexibility / Strength / Balance / Recovery / Breathwork
- Tap → expand → **✏️ Edit** or **🗑️ Delete**

### 🤏 Hangboard (Outdoor tab)
- Grip type, +weight (kg), hang time (s), edge size (mm)
- Tap → expand → **✏️ Edit** or **🗑️ Delete**

### 🌤️ Weather + Activity Planner
- **City search** with autocomplete + OK button
- **GPS fallback** via browser geolocation
- Home screen: temperature, wind, humidity, animated icon
- **Activity recommendation card**: 5 activities (🥾🏃🧗🏋️🧘) rated Avoid→Perfect
- Smart tips based on conditions (storm, rain, heat, cold)
- 🥾 Hike rating: Go! / Check / Nope

### ⌚ Smartwatch (5 types)
- Garmin / Galaxy Watch / Apple Watch / Fitbit / Other
- Morning check-in with custom metrics per watch
- Tap entry → metric bars + smart insights + overall score

### 📊 Analytics Dashboard
- **6 summary cards** (Volume, PRs, Climb, Hike, Run, Yoga) — tap to navigate
- 📏 Body: weight trend ±kg, measurements, body fat %
- 💪 Strength: lift progression with ±kg, volume chart
- ⌚ Recovery: readiness/sleep trends, averages
- 🏆 PRs: ranked by estimated 1RM
- Date filters: 1W / 1M / 3M / All
- Animated SVG charts

### 📋 Reminders
- Dismissible badges for: watch check-in, body progress, incomplete workouts, missing climb/hike/run/yoga entries
- Badge count on nav icon

### 👤 Profile
- Name, age, height, weight, goal weight, city
- Auto BMI + goal progress bar
- View/Edit toggle

---

## ✏️ Edit & Delete
Every outdoor entry (climb, hike, run, yoga, hangboard):
```
Tap entry → details expand → ✏️ Edit (inline form) or 🗑️ Delete
```

## 💾 Data & Backup
- 📤 Export JSON · 📥 Import JSON · 🗑 Delete all
- All data in **localStorage** — nothing leaves your device

## 🧪 Demo Data
Import `gymclimb-demo-data.json`:
39 climbs · 9 runs · 7 hikes · 7 yoga · 6 hangboard · 36 Garmin · 12 weeks progress · 3 PRs

---

## 🛠️ Tech
Single `index.html` · React 18 + Babel (cdnjs) · Custom SVG charts · Open-Meteo weather · i18n EN/HR/DE

### Deploy
```
Upload index.html + README.md → GitHub repo → Settings → Pages → main → Save
```

## 📋 Changelog
| Ver | Changes |
|-----|---------|
| **6.0** | 🏃 Running + 🧘 Yoga, activity planner, 6 analytics cards, run/yoga reminders |
| **5.3** | ✏️ Edit entries, GPS weather, reliable delete |
| **5.2** | 🌐 3 languages, weather in climb/hike |
| **5.0** | ⌚ Multi-watch, smart insights, analytics |

<p align="center"><sub>Built with ❤️ for athletes who do it all</sub></p>
