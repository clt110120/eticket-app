# E-Ticket Generator — Prime Lanka Tours

Upload airline itinerary PDFs → Gemini AI extracts flight data → Branded e-ticket PDF.

## Deploy to Railway (Free)

1. Push this repo to GitHub
2. Go to railway.app → New Project → Deploy from GitHub
3. Add environment variable: `GEMINI_API_KEY=AIza...`
4. Done!

## Get Free Gemini API Key

1. Go to aistudio.google.com
2. Sign in with Google account
3. Click "Get API key" → Create API key
4. Copy and paste into Railway environment variables

## Local Development

```bash
pip install -r requirements.txt
export GEMINI_API_KEY=AIza...your-key...
python app.py
# Open http://localhost:5000
```

## Environment Variables

| Variable | Description |
|---|---|
| `GEMINI_API_KEY` | From aistudio.google.com — Free, no card needed |
| `PORT` | Set automatically by Railway |
