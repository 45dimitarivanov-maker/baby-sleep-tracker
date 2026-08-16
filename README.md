# 🌙 Baby Sleep Tracker

A simple, single-file web app to track a baby's naps, night sleep, and awake time.

**Live app:** https://45dimitarivanov-maker.github.io/baby-sleep-tracker/

## Features

- **Quick nap entry** — Log naps with optional "put down" / "fell asleep" / "woke up" times and one-tap **Now** buttons. Naps that cross midnight are handled automatically.
- **Night sleep, split across the evening and morning** — In the evening, tap **Log bedtime** to record when the baby went down. The next morning, the app greets you with **Good morning** and the bedtime already filled in — just enter the wake time (or tap **Woke now**) to complete the night. A night counts toward the day it *started*.
- **Daily dashboard** — Total sleep, awake time, night sleep, and day naps for any day, with day-to-day navigation.
- **Editable sleep log** — Edit or delete any logged sleep inline, including a night that's still in progress.
- **Awake windows** — See how long the baby was awake between each sleep, including the morning window from last night's wake to the first nap.
- **Night details** — Record how many times night sleep was interrupted, and add free-text notes to any nap or night sleep. Both show in the sleep log.
- **Statistics** — Daily averages over a period you choose with a slider (2–30 days), including average night interruptions.

## Privacy

All data is stored in your browser's **localStorage** — nothing is sent anywhere. It stays on the device you use.

## Running locally

Just open `index.html` in any modern browser. No build step, no dependencies.
