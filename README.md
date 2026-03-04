# 🔬 Deep Research Agent

AI-powered research dashboard. Enter any topic, watch the agent think, search, and write a full report — live.

**Week 3 of 12** — One product shipped every week.

## Deploy on Netlify

1. Push this repo to GitHub
2. Go to [Netlify](https://app.netlify.com) → **Add new site** → **Import from GitHub**
3. Select this repo — no build settings needed
4. **Add environment variable:**
   - Go to **Site settings** → **Environment variables**
   - Add: `ANTHROPIC_API_KEY` = your Claude API key
5. **Redeploy** and you're live

## How It Works

- `index.html` — the entire frontend (glassmorphism dashboard)
- `netlify/functions/claude.js` — serverless proxy that calls Claude API securely
- Your API key stays server-side, never exposed to the browser

## Tech Stack

- Vanilla HTML/CSS/JS (single file frontend)
- Netlify Functions (serverless Claude API proxy)
- Claude Sonnet 4 with web search
- Zero npm dependencies

## License

MIT
