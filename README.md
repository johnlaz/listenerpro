# Listener Pro 🎙

A real-time AI conversational support PWA powered by the Gemini Live API.

## Features

- **4 Support Modes** — Supportive, Engaged, Logical, Baseline
- **Real-time voice conversation** with Gemini 2.5 Flash Native Audio
- **Live soundbar** showing actual mic input levels
- **Ghost Mode** — black screen with corner tap zones for stealth use
- **⚡ Reply Now** — force an immediate AI response mid-conversation
- **Session History** — AI-generated summaries with topic, tone, insight & repair phrase
- **Full session log viewer** — review complete transcripts
- **PWA installable** — works as a native app on Android & iOS

## Setup

1. Get a free API key from [Google AI Studio](https://aistudio.google.com)
2. Open the app and paste your key on the setup screen
3. Tap **CONNECT**, allow microphone, and start talking

## Deploy to Netlify

1. Fork or upload this repo
2. Drag the folder to [app.netlify.com/drop](https://app.netlify.com/drop)
3. Open the `https://` URL on your phone

## File Structure

```
/
├── index.html          # Main app
├── manifest.json       # PWA manifest
├── sw.js               # Service worker (offline support)
├── favicon.ico         # Browser favicon
├── apple-touch-icon.png
├── icon-72x72.png
├── icon-96x96.png
├── icon-128x128.png
├── icon-144x144.png
├── icon-152x152.png
├── icon-192x192.png
├── icon-384x384.png
└── icon-512x512.png
```

## Notes

- Microphone **requires HTTPS** — always use the `https://` Netlify URL
- API key is stored in localStorage only, never transmitted anywhere except Google's API
- The app uses `gemini-2.5-flash-native-audio-latest` for the Live API
