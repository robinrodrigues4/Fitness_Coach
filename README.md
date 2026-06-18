# 🔥 My Fitness Plan

A fully personalised daily diet + home/gym workout tracker — built as a single HTML file, runs entirely in the browser.

## Features

- **Personalised setup** — onboarding collects your age, weight, target, schedule, commute, diet, and workout preferences
- **Dynamic calorie & macro targets** — calculated using Mifflin-St Jeor BMR × activity factor, auto-adjusts if progress stalls
- **7-day rotating meal plan** — 3 options per meal slot, every day, remembers your choice
- **Home or gym workouts** — bodyweight or equipment, beginner to advanced, auto-progresses
- **AI Coach** — powered by Claude, context-aware answers about your plan
- **Natural language food logging** — type "I had 2 rotis and dal", AI estimates calories
- **Calorie tracker** — manual + quick-add + restaurant/canteen items
- **Analytics** — weight trend chart, body composition, workout volume
- **Progress tracking** — weight log, waist log, progress photos, before/after compare
- **Daily check-in streak** — Duolingo-style habit tracker
- **Supplement tracker**, **grocery list**, **recipe cards**
- **WhatsApp share card** — weekly progress summary
- **Dark/light mode**, **vacation mode**, **deload weeks**
- **All data stored locally** — nothing sent to any server except AI queries

## Setup

1. Fork or clone this repo
2. Go to **Settings → Pages → Deploy from branch → main → / (root)**
3. Your site will be live at `https://yourusername.github.io/my-fitness-plan/`
4. Open on phone → Share → Add to Home Screen

## Tech

Pure HTML + CSS + JavaScript. No framework, no build step, no server.
Uses [Chart.js](https://chartjs.org) for analytics charts.
AI features use the [Anthropic API](https://anthropic.com) — requires HTTPS (works on GitHub Pages).

## Privacy

All personal data (weight, meals, workouts, photos) is stored in your browser's `localStorage`. Nothing leaves your device except AI Coach queries sent to the Anthropic API.
