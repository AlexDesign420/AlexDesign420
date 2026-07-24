<p align="center">
  <img src="./assets/hero.svg" alt="Alex — macOS widgets, web apps and AI-assisted developer tools" width="100%">
</p>

---

## Featured Projects

### 🤖 Claude Mac App

A native macOS desktop application for [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) — embedded PTY terminal, agent command center, SQLite persistence and local LLM integration via LM Studio.

**Stack:** Tauri 2 · React 19 · TypeScript · SQLite · node-pty · Rust

[![Release](https://img.shields.io/github/v/release/AlexDesign420/claude-mac?style=flat-square&color=24C8D8)](https://github.com/AlexDesign420/claude-mac/releases)
[→ Repository](https://github.com/AlexDesign420/claude-mac)

---

### 🎓 Syntax Sync

A native macOS wrapper for the Syntax Institut learning platform. SwiftUI sidebar, WKWebView session persistence, JavaScript data bridge and offline JSON cache.

**Stack:** Swift · SwiftUI · WKWebView · JavaScript

[![Release](https://img.shields.io/github/v/release/AlexDesign420/SyntaxMacOs?style=flat-square&color=F05138)](https://github.com/AlexDesign420/SyntaxMacOs/releases)
[→ Repository](https://github.com/AlexDesign420/SyntaxMacOs)

---

### ❤️ Health Advisor

A SwiftUI iOS app that reads Apple Health data — steps, activity, sleep, heart rate — and generates simple, visual daily health insights with charts and trend analysis.

**Stack:** Swift · SwiftUI · HealthKit · Swift Charts

[![Release](https://img.shields.io/github/v/release/AlexDesign420/health-app?style=flat-square&color=30D158)](https://github.com/AlexDesign420/health-app/releases)
[→ Repository](https://github.com/AlexDesign420/health-app)

---

### 🏎️ F1 Live Widget

A real-time Formula&nbsp;1 desktop widget for macOS ([Übersicht](https://tracesof.net/uebersicht/)).

- Live standings, race control, team radio
- Audio streams with integrated playback
- German text-to-speech commentary
- Weather, championship tables, race calendar countdown

**Stack:** Python · Flask · Übersicht · OpenF1 API · Jolpica API

[![Release](https://img.shields.io/github/v/release/AlexDesign420/f1-widget?style=flat-square&color=E8002D)](https://github.com/AlexDesign420/f1-widget/releases)
[→ Repository](https://github.com/AlexDesign420/f1-widget)

---

### ⚽ WM 2026 Widget

A real-time FIFA World Cup 2026 desktop widget for macOS.

- Live scores from ESPN API
- 20+ radio streams (ARD, ZDF, BBC, NPR, …)
- German TTS commentary for goals and events
- Play-by-play feed and live ticker panel
- Responsive layout for 1440p – 4K displays

**Stack:** JavaScript · Python · Flask · Übersicht · ESPN API

[![Release](https://img.shields.io/github/v/release/AlexDesign420/wm2026-widget?style=flat-square&color=007A3D)](https://github.com/AlexDesign420/wm2026-widget/releases)
[→ Repository](https://github.com/AlexDesign420/wm2026-widget)

---

## Open Source Contributions

### snow-cli — agent stream format fix

Six internal agents of [`MayDay-wpf/snow-cli`](https://github.com/MayDay-wpf/snow-cli) read the raw
SSE shape `chunk.choices[0].delta.content` while the stream had already been normalised to
`{ type: 'content', content }`. The mismatch only surfaced with OpenAI-compatible endpoints
(LM Studio, Ollama, vLLM, DeepSeek) and failed **silently** — the summary agent, the vision agent
and, most importantly, the auto-compaction agent simply received empty responses.

The fix removes the branch entirely and always reads the unified format: **24 insertions,
91 deletions**, `tsc` and `prettier` clean.

[![PR #193](https://img.shields.io/badge/PR%20%23193-merged-8957E5?style=flat-square&logo=github)](https://github.com/MayDay-wpf/snow-cli/pull/193)
&nbsp;Merged 2026-07-17 · shipped in `v0.8.19`

[→ View the pull request](https://github.com/MayDay-wpf/snow-cli/pull/193)

---

## Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)

**Tools & Platforms**

![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?logo=tauri&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?logo=apple&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)

---

## Focus Areas

- **AI-assisted development** — Local LLM workflows, Claude Code, coding agents, LM Studio
- **Native macOS apps** — SwiftUI, WKWebView, Tauri-based desktop tools
- **Native iOS apps** — SwiftUI, HealthKit, Apple platform development
- **macOS desktop widgets** — Übersicht widgets with live data, audio and TTS
- **Live data integrations** — Sports APIs, streaming, real-time updates
- **Clean UI & documentation** — Readable code, structured READMEs, open source

---

## Project Philosophy

I build iteratively, test ideas in real projects and improve step by step.  
Every repository is designed to be usable, documented and presentable — even prototypes.

---

## Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=AlexDesign420&show_icons=true&theme=dark&hide_border=true&count_private=true)

---

## Contact

📫 **info.dejan@proton.me** · [GitHub](https://github.com/AlexDesign420)

<!-- profile -->
