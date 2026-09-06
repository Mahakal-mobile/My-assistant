# Guru – आपका ऑल-इन-वन सहायक

Modern mobile-first PWA-style web app with dark theme.

## Features

- **Chat** – Live AI conversational assistant (text + voice)
- **Memory** – Long-term notes stored in browser localStorage
- **Reply** – Smart auto-reply generator (Friendly / Formal / Strict / Concise / Funny + All)
- **Shield** – Heuristic URL/phishing scanner + Privacy Master Switch
- **EN / हिंदी** toggle with persistence
- Draggable floating chat bubble
- Fully responsive & mobile-first

## How to Deploy on Vercel (via GitHub)

### 1. Create GitHub Repository
1. Go to [GitHub](https://github.com) → New repository
2. Name it `guru-app` (or anything)
3. Keep it Public
4. **Do not** initialize with README (we already have one)

### 2. Upload these files
- `index.html`
- `manifest.json`
- `README.md`

You can either:
- Drag & drop the files on GitHub, **or**
- Use Git commands:

```bash
git init
git add .
git commit -m "Initial commit - Guru App"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/guru-app.git
git push -u origin main
```

### 3. Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and login with GitHub
2. Click **Add New Project**
3. Import your `guru-app` repository
4. Framework Preset → **Other** (or leave blank)
5. Click **Deploy**

Done! You will get a live URL like `https://guru-app.vercel.app`

### Optional: Custom Domain
Vercel dashboard → Settings → Domains → Add your domain.

---

Made with ❤️ for easy deployment.
