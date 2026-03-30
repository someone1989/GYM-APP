# 🏔️ GymClimb Tracker

A standalone workout + climbing + hiking tracker optimized for iPhone with Garmin Fenix 7X integration.

## Features

- **7-day training program** (Mass + Climbing) with customizable exercises
- **Set-by-set tracking** with weight, reps, RPE, and previous week comparison
- **1RM calculator** (Epley formula) and automatic PR detection
- **Climbing log** with bouldering grades (V0–V12), sport grades (4a–8a), flash/redpoint/project tracking
- **Bouldering pyramid** visualization
- **Hangboard / finger strength** tracker
- **Hiking log** with distance, elevation, duration, difficulty
- **Garmin Fenix 7X integration** – morning check-in (Training Readiness, Body Battery, Sleep Score, Recovery Time) and post-workout data (HR, calories, Training Effect, Load)
- **Recovery dashboard** with smart overtraining alerts
- **Charts** – Training Readiness trends, lift progression, weekly volume
- **Reminders** – Garmin check-in, weekly progress, incomplete workouts
- **Data export/import** – backup and transfer between devices
- **PWA support** – install as app on iPhone home screen
- **100% offline** – no server, no account, all data stored locally

## Setup (GitHub Pages)

1. Create a new GitHub repository (e.g. `gymclimb`)
2. Upload `index.html` to the repository root
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Wait ~1 minute, your app is live at: `https://YOUR-USERNAME.github.io/gymclimb/`

## How to install on iPhone

1. Open the GitHub Pages URL in **Safari** (not Chrome)
2. Tap the **Share** button (□↑)
3. Tap **"Add to Home Screen"**
4. Name it **GymClimb**
5. Tap **Add**
6. Done – the app icon appears on your home screen 🏔️

## Data

- All data is stored in **localStorage** on the device
- Nothing is sent to any server
- Use **Settings → Export** to backup your data as JSON
- Use **Settings → Import** to restore data from a backup
- Share the JSON file to transfer data to another device

## Tech

Single HTML file, no build step. Uses React 18, Recharts, and Babel standalone from CDN.
