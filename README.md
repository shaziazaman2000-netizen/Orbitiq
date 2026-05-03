# ✦ ORBITIQ — Orbital Intelligence Suite

> Ten AI-powered tools in one platform. Intelligence that revolves around you.

---

## 🚀 Deploy FREE in 5 Minutes (Vercel)

### Step 1 — Get Your Free API Key
1. Go to **https://console.anthropic.com**
2. Sign up for a free account
3. Click **API Keys** → **Create Key**
4. Copy your key (starts with `sk-ant-...`)

### Step 2 — Upload to GitHub
1. Go to **https://github.com** → sign up free
2. Click **New Repository** → name it `orbitiq`
3. Upload ALL these project files
4. Click **Commit changes**

### Step 3 — Deploy on Vercel (100% Free)
1. Go to **https://vercel.com** → sign up with GitHub
2. Click **Add New Project** → Import your `orbitiq` repo
3. Click **Environment Variables** → Add:
   - Key: `ANTHROPIC_API_KEY`
   - Value: `sk-ant-...` (your key from Step 1)
4. Click **Deploy** ✅

### Step 4 — Your app is LIVE!
Vercel gives you a free URL like:
`https://orbitiq.vercel.app`

---

## 🌐 Custom Domain (Optional, ~$10/year)
1. Buy `orbitiq.com` on **Namecheap.com**
2. In Vercel → Settings → Domains → Add your domain
3. Follow the DNS instructions (takes 5 minutes)

---

## 📁 Project Structure
```
orbitiq/
├── index.html          ← App entry point
├── vite.config.js      ← Build config
├── package.json        ← Dependencies
├── vercel.json         ← Deployment config
├── .env.example        ← API key template
├── api/
│   └── chat.js         ← Secure API route (hides your key)
├── public/
│   └── favicon.svg     ← App icon
└── src/
    ├── main.jsx        ← React entry
    └── App.jsx         ← Full ORBITIQ app
```

---

## ✦ Features
- 10 Live AI Tools powered by Claude
- Voice Input · Dark/Light Mode · PDF Export
- Multilingual · Favorites · Daily Tips
- Session History · Copy Responses

---

Built with React + Vite + Claude AI · Free to deploy · ORBITIQ © 2026
