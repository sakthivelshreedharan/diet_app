# 🏠 Chennai Health Tracker

Personalised meal planning + activity tracking for your household.  
**Works on any device. No backend. No API key needed. Free hosting.**

🌐 **Live app:** `https://YOUR_GITHUB_USERNAME.github.io/chennai-health-tracker`

---

## ✨ Features

- **🍛 Daily Meal Planner** — Pick your ration, get a lazy meal plan with exact quantities for all household members
- **🏃 Activity Tracker** — Log walks, yoga, housework. Track tea/coffee cups per person
- **📊 Progress** — Weekly charts, smart suggestions based on your actual data
- All data saved in your browser — works offline after first load

---

## 🚀 Deploy to GitHub Pages (Step by Step)

### Step 1 — Create GitHub repo

1. Go to [github.com/new](https://github.com/new)
2. Name it: `chennai-health-tracker`
3. Keep it **Public**
4. Click **Create repository**

### Step 2 — Edit package.json

Open `package.json` and change line 5:
```json
"homepage": "https://YOUR_GITHUB_USERNAME.github.io/chennai-health-tracker",
```
Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.

### Step 3 — Install & deploy

Open terminal in the project folder:

```bash
# Install dependencies
npm install

# Test it works locally first
npm start

# Deploy to GitHub Pages
npm run deploy
```

That's it! Your app will be live at:  
`https://YOUR_GITHUB_USERNAME.github.io/chennai-health-tracker`

> First deploy takes 2–3 minutes to go live. After that, updates appear in ~30 seconds.

### Step 4 — Push source code (optional but recommended)

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/chennai-health-tracker.git
git push -u origin main
```

---

## 💻 Run Locally (Lab Laptop / Home PC)

```bash
npm install
npm start
# Opens at http://localhost:3000
```

---

## 📱 Use on Phone

Once deployed, open the GitHub Pages URL on your phone's browser.  
On Android: tap the 3-dot menu → "Add to Home Screen" → works like an app!  
On iPhone: tap Share → "Add to Home Screen"

---

## 🔄 Update the App

Whenever you make changes:
```bash
npm run deploy
```
Live in ~30 seconds.

---

## 📦 Tech Stack

| Item | Detail |
|------|--------|
| Framework | React 18 |
| Charts | Recharts |
| Data storage | Browser localStorage |
| Hosting | GitHub Pages (free) |
| AI / Backend | None needed |

---

## 🧪 How Meal Planning Works (No AI)

The app uses smart built-in logic based on what you select:
- Detects if you have rice → applies cool rice trick reminder
- Detects protein source → builds appropriate meal with correct portions
- Scales all quantities by number of people in household
- Dinner always suggests half-rice, lunch is full portion
- Breakfast always suggests a lazy/no-cook option (overnight oats, boiled eggs, idli)

---

## 📊 Data & Privacy

All data is stored **only in your browser's localStorage**.  
Nothing is sent to any server. Completely private.  
Clearing browser data or opening on a new device starts fresh.

---

Made with ❤️ for Chennai households — eat healthy without giving up white rice!
