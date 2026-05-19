# Ayana SEO & Content Agent

A standalone AI-powered SEO and content tool for Ayana Dermatology & Aesthetics.

## Deploy to Vercel (5 steps)

### 1. Upload to GitHub
- Go to github.com → New repository
- Name it: `ayana-agent`
- Upload all files (drag & drop the folder)

### 2. Connect to Vercel
- Go to vercel.com → Add New Project
- Import your `ayana-agent` GitHub repo
- Click Deploy (don't change any settings)

### 3. Add your API Key
- In Vercel → your project → Settings → Environment Variables
- Add: `ANTHROPIC_API_KEY` = your key from console.anthropic.com
- Click Save

### 4. Redeploy
- Go to Deployments → click the 3 dots → Redeploy

### 5. Done
- Your app is live at: `https://ayana-agent.vercel.app`
- Bookmark it — works in any browser, any device, anytime

## Files
- `public/index.html` — the full app UI
- `api/generate.js` — the backend that calls Anthropic securely
- `vercel.json` — routing config
