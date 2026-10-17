# 🌴 Djerba Experience

A multilingual mobile-first tourism web app for **Djerba, Tunisia** — featuring island tours, pirate boat adventures, and Sahara desert excursions.

## 🌍 Languages
- 🇫🇷 French
- 🇬🇧 English
- 🇩🇪 German

Auto-detects the phone's browser language. Includes a sticky language switcher bar.

## 🎯 Activities
1. **Tour de l'Île** — Full island circuit
2. **Bateaux Pirates** — Pirate boat sea adventure
3. **Excursion Désert** — Sahara desert camel excursion

## 📲 Bookings
All reservations are handled via WhatsApp: **+216 28 322 011**

## 🎬 Videos (TikTok-style Reel)
Drop your MP4 video files into the `videos/` folder with these names:
- `videos/tour_ile.mp4`
- `videos/bateaux_pirates.mp4`
- `videos/excursion_desert.mp4`

The app auto-detects the files. If not found, it shows image placeholders.

## 📁 Project Structure
```
djerba/
├── index.html              ← Main app (single file)
├── images/
│   ├── tour_ile.jpg
│   ├── bateaux_pirates.jpg
│   └── excursion_desert.jpg
├── videos/                 ← Drop your MP4s here
│   ├── tour_ile.mp4
│   ├── bateaux_pirates.mp4
│   └── excursion_desert.mp4
├── .nojekyll               ← Required for GitHub Pages
└── README.md
```

## 🚀 Deploy to GitHub Pages

### Step 1 — Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit - Djerba Experience app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/djerba.git
git push -u origin main
```

### Step 2 — Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: `main`, folder: `/ (root)`
5. Click **Save**

### Step 3 — Your site is live!
After ~1 minute your app will be at:
```
https://YOUR_USERNAME.github.io/djerba/
```

## 🛠️ Tech Stack
- Pure HTML + CSS + Vanilla JavaScript
- No frameworks, no build step required
- Google Fonts (Outfit)
- Mobile-first responsive design
