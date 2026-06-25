# VoiceFlow

A clean, distraction-free **text-to-speech web app** for study and work. Single self-contained `index.html` — no build step, no backend. Open it in a browser or host it as a static site.

## Features
- **Reader** with word-by-word highlighted playback (Web Speech API); sentence-level highlight fallback on iOS
- **Library** with paste / PDF / DOCX / TXT import, folders, and saved reading progress
- **AI Study Tools** — Summarize (with interview pro-tips), Flashcards, Quiz, and grounded Q&A (bring your own Anthropic API key)
- **Voice cloning** via ElevenLabs (bring your own key) + 6 built-in voices
- **Audio / MP3 export** and **Podcast mode** (desktop browsers)
- Notes & highlights, Study Dashboard, pronunciation rules, dark/light themes, dyslexia-friendly font
- Responsive: slide-over panels on mobile, three-pane layout on desktop

## Use it
Open `index.html` in a modern browser (Chrome or Edge recommended). All data stays in your browser's localStorage; API keys are entered per-device and never leave your browser except to call the respective service.

## AI keys (optional)
- **Anthropic** (AI tools): Settings → AI
- **ElevenLabs** (voice cloning, paid plan): Settings → Voice

Without keys, the AI tools run in demo mode.
