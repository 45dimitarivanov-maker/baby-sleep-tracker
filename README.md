# 🌙 Baby Sleep Tracker

A simple, single-file web app to track a baby's naps, night sleep, and awake time.

**Live app:** https://45dimitarivanov-maker.github.io/baby-sleep-tracker/

## Features

- **Quick nap entry** — Log naps with optional "put down" / "fell asleep" / "woke up" times. Naps that cross midnight are handled automatically.
- **Night sleep, split across the evening and morning** — The day reads top to bottom: **Good morning** (enter the wake time, night interruptions, and any notes to complete last night's sleep) → **Add a nap** → **Tonight's bedtime** (log an optional "put down" time and when the baby fell asleep; you'll add the wake time tomorrow morning). Each night is its own record — logging tonight's bedtime never overwrites a past night. A night counts toward the day it *started*.
- **Timeline layout** — Each day shows the night sleep first (bedtime → wake), then the naps in chronological order below it.
- **Daily dashboard** — Total sleep, awake time, night sleep, and day naps for any day, with day-to-day navigation.
- **Editable sleep log** — Edit or delete any logged sleep inline, including a night that's still in progress.
- **Awake windows** — See how long the baby was awake through the day: from the morning wake to the first nap, and between each nap.
- **Night details** — Record how many times night sleep was interrupted, and add free-text notes to any nap or night sleep. Both show in the sleep log.
- **Statistics** — Daily averages over a period you choose with a slider (2–30 days), including average night interruptions.

## Privacy

All data is stored in your browser's **localStorage** — nothing is sent anywhere. It stays on the device you use.

## Running locally

Just open `index.html` in any modern browser. No build step, no dependencies.
