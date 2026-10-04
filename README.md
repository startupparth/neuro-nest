# 🧠 Neuro Nest — Mind Operating System

**An emotion-aware AI companion that understands how you feel, tracks your mental well-being, and suggests what to do next.**

Neuro Nest is a complete mental-wellness app in a **single HTML file** — no build tools, no server, no dependencies. Open it in any browser and everything works offline. All data stays on your device.

---

## ✨ Features

| Module | What it does |
|---|---|
| 🏠 **Dashboard** | Vitality Score, day streak, XP, daily mood check-in, personalized AI suggestions |
| 💬 **AI Companion** | Emotion-aware chat that detects sadness, anxiety, anger, burnout, loneliness, sleep & focus issues — then suggests what to do (breathing, focus sprint, check-in, or booking a professional). Crisis messages instantly surface Indian helplines (Tele-MANAS 14416, AASRA, iCall) |
| ⏱️ **Focus Mode** | Real Pomodoro timer (Deep Focus 25 min / Quick Sprint 10 min) with **live-generated ambient soundscapes** — rain, ocean, lo-fi chords, forest birds (WebAudio, no audio files) |
| 🧩 **Cognitive Lab** | 4 playable brain games: Memory Matrix, Focus Trainer, Logic Chains, Speed Processing — with levels, XP and Brain Score |
| 🩺 **Therapy Hub** | Book sessions with verified psychologists & psychiatrists — pick date, time slot and mode (video/audio/chat). Cancel or join waitlists |
| 📊 **Analytics** | Mood, sleep & focus charts, productivity heatmap, emotion mix and weekly AI insights — computed from your own check-ins |
| 🛡️ **Preventive AI** | Burnout risk, stress level, sleep debt and recovery score with early-warning health alerts |
| ♿ **Neurodiverse Mode** | Reduced motion, high contrast, color-blind palette, large text and screen-reader support — all genuinely functional |
| ⚙️ **Settings & Pricing** | Profile, Hindi/Hinglish/English interface, 4 AI personalities, Free vs Pro (₹299/month) plan with a 10-message/day free limit |

## 🚀 Quick start

```bash
git clone https://github.com/YOUR_USERNAME/neuro-nest.git
cd neuro-nest
open index.html      # macOS
start index.html     # Windows
xdg-open index.html  # Linux
```

Or simply **download `index.html` and double-click it**. That's the whole app.

## 🛠️ Tech stack

- **One file**: HTML + CSS + vanilla JavaScript (~2,000 lines, ~134 KB)
- **Zero dependencies**, zero network calls, works fully offline
- **Web Audio API** — soundscapes synthesized in real time
- **localStorage** — private, persistent data on your device
- Rule-based emotion engine with intent detection and crisis-safety flows

## 🔒 Privacy

Everything — mood logs, chats, bookings, XP — is stored **only in your browser's localStorage**. Nothing is uploaded anywhere. No analytics, no trackers, no cookies.

## ⚠️ Disclaimer

Neuro Nest is a demo and is **not a medical device**. It does not diagnose, treat or replace professional care.

**If you are in crisis, please reach out:**
- 🇮🇳 Tele-MANAS (Govt of India): **14416** or 1-800-891-4416 — 24×7, free
- AASRA: +91 9820466726 (24×7)
- iCall: 9152987821 (Mon–Sat, 10 AM–8 PM)
- Emergency: **112**

## 🗺️ Ideas for v2

- [ ] Connect the AI companion to a real LLM API (GPT / Claude / Gemini)
- [ ] Razorpay/Stripe checkout for Pro & therapy sessions
- [ ] Zoom/Google Meet integration for therapy sessions
- [ ] PWA install + mobile app wrapper (Capacitor)
- [ ] Multi-device sync with end-to-end encryption

## 📄 License

[MIT](LICENSE) — free to use, modify and build upon.
