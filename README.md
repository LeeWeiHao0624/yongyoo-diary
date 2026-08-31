# 💕 The YongYoo Diary

A private, single-file diary website that archives **every little moment between Yongjun and Yoorin** — and turns it into a love story with graphs.

Made with 💗 for Yongjun & Yoorin.

## ✨ Features

- 🔐 **Secret password lock** (just for fun — set it on first launch)
- ✍️ **Daily memories** — date, title, story, 1–5 heart closeness rating, tags, and optional photos
- 🌡️ **Love Meter** — every memory adds points (♥ × 2); silent days slowly drain it. Hit 100% for the big confetti moment 💥
- 📖 **Timeline** — the whole story as a scrolling feed with edit/delete
- 📊 **Stats** — closeness-over-time graph, streaks, averages, tag frequency
- 🏅 **13 milestone badges** to unlock (streaks, first text, meter milestones...)
- ✨ **Demo data** button so you can preview everything instantly
- 💾 **Backup & restore** via JSON export/import

## 🚀 How to run

No installs needed — it's one file:

1. Double-click `index.html` (opens in your browser)
2. Create your secret password
3. Start writing (or click **Load demo memories** to preview)

## 🌍 How to share it (free hosting)

1. Create a repo on GitHub, upload `index.html`
2. Repo **Settings → Pages** → deploy from `main` branch
3. Send the link — e.g. `https://yourname.github.io/yongyoo-diary`

## 🗄️ Where is my data?

Everything lives in **your browser's localStorage** — nothing is sent anywhere.
Export a backup from ⚙️ Settings before clearing browser data or switching computers.
Photos are compressed to ~720px so they fit in browser storage.

## 🔮 Future ideas (Version 2)

- Tiny backend (Node.js + SQLite) so Yongjun can read it on her phone
- Auto-predict the "she says yes" date from the closeness trend
- Monthly recap cards you can share
