# 🌟 Word Adventure! / 單字大冒險

A bilingual word puzzle game for kids aged 5–12, playable in the browser with no install required.

**Live:** https://hsinhoyeh.github.io/word-adventure/

---

## Features

- **Three themes** — Airline ✈️, Bus 🚌, Ocean 🌊
- **Three difficulty levels** — Easy (5–7 yrs) / Medium (8–10 yrs) / Hard (10–12 yrs) with countdown timer
- **45 vocabulary words** — 5 per theme per difficulty, with English and Traditional Chinese
- **Bilingual** — English and Traditional Chinese (繁體中文) with Bopomofo / 注音符號 annotation
- **Voice reading** — clue sentences are read aloud automatically via the Web Speech API; tap 🔊 to replay
- **Leaderboard** — top scores per difficulty, saved in the browser
- **50/50 hint** — removes two wrong answers when you're stuck
- **Social sharing** — share your score on X, Facebook, LINE, and WhatsApp

## How to play

1. Enter your name and pick a difficulty
2. Choose a theme (Airline / Bus / Ocean)
3. Read the clue sentence and pick the word that fills the blank
4. Answer 5 questions — each correct answer teaches you the English word and its Chinese translation with zhuyin

## Word themes

| Theme | Sample words (Easy → Hard) |
|-------|---------------------------|
| ✈️ Airline | fly, sky, seat → pilot, ticket, cargo → passport, luggage, captain |
| 🚌 Bus | bus, stop, door → driver, route, window → schedule, passenger, destination |
| 🌊 Ocean | sea, fish, wave → ocean, sailor, anchor → captain, dolphin, lighthouse |

## Tech

Single self-contained `index.html` — no build step, no dependencies. Uses:

- Web Speech API for text-to-speech (`zh-TW` / `en-US`)
- Inline Bopomofo annotator for zhuyin display
- `localStorage` for leaderboard and language preference

## Development

```bash
git clone git@github-hsinhoyeh:hsinhoyeh/word-adventure.git
open word-adventure/index.html
```

Deployments go live automatically via GitHub Pages on every push to `master`.
