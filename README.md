# FitOS — Personal Fitness Dashboard

A complete personal fitness tracker built as a single HTML file. No server, no backend, no accounts. Everything runs in your browser and data is saved locally.

## 🚀 Live App

**→ [Open FitOS](https://gramprayong.github.io/fitos)**

## Features

- 📊 **Dashboard** — Daily overview, weight trend chart, calendar with full history
- ⏰ **Today** — Live calorie ring, energy balance, macro bars, meal log
- 🍱 **Food** — USDA + Open Food Facts (4M+ foods), Thai local database, adjustable IF window
- 📈 **Body** — Weight tracking, TDEE calculator (Mifflin / Katch-McArdle), milestones
- 😴 **Sleep** — Log bedtime/wake, quality rating, 7-day chart, sleep protocol
- 💪 **Workout** — Hybrid plan (3 lifts + 3 runs), per-exercise equipment↔bodyweight toggle, suggested weights
- 🦵 **Myrtle** — IT band rehab routine, 12 exercises, streak tracker

## Deploy to GitHub Pages (5 minutes)

### Step 1 — Create repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `fitos`
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Upload the file
```bash
# Option A: GitHub website (easiest)
# Drag and drop index.html into the repository

# Option B: Command line
git clone https://github.com/YOUR-USERNAME/fitos.git
cd fitos
cp /path/to/fitos-complete.html index.html
git add index.html
git commit -m "Initial FitOS deploy"
git push
```

### Step 3 — Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source**, select `Deploy from a branch`
4. Select branch: `main` / folder: `/ (root)`
5. Click **Save**

### Step 4 — Access your app
Your app will be live at:
```
https://YOUR-USERNAME.github.io/fitos
```
(Takes 1-2 minutes to deploy after saving)

## Data & Privacy

- All data stored in your **browser's localStorage** — never leaves your device
- No accounts, no tracking, no servers
- Works offline after first load
- To back up: open browser DevTools → Application → Local Storage → export

## Food Database Sources

| Source | Size | Best for |
|--------|------|----------|
| USDA FoodData Central | 300k+ | Raw foods, generics, US brands |
| Open Food Facts | 4M+ | Branded/packaged, Thai products, restaurant chains |
| Thai Local DB | ~25 foods | Street food, 7-Eleven Thailand, restaurants |

## Fasting Windows

| Protocol | Fast | Eat |
|----------|------|-----|
| 16:8 Classic | 16h | 12PM–6PM |
| 16:8 Extended | 16h | 12PM–7PM (default) |
| 18:6 Lean | 18h | 1PM–7PM |
| 18:6 Late | 18h | 2PM–8PM |
| 20:4 Warrior | 20h | 12PM–4PM |
| Custom | — | Set any hours |

## Personal Profile (pre-configured)
- 34M · 171cm · 82kg → target 75kg
- IT band injury (left) — Myrtle routine included
- Work schedule: 9AM–6PM
- Running: 7–9PM evenings
- Home equipment: Dumbbells + resistance bands
