# Cramp Logger

A one-tap stomach symptom tracker that runs in your phone's browser and saves to the phone itself. It has no account, no server and no App Store.

## What it logs

- **Symptoms:** cramps, severe cramps, nausea and morning stomach irritation, each with an optional 1–5 severity
- **Food & drink:** meals (what you ate, meal type, portion size, trigger tags), coffee, alcohol and water
- **Medication & body:** medication (saved meds become one-tap, and as-needed meds get a "did it help?" follow-up), bowel movements, sleep, stress and exercise

Each tap saves straight away with the date and time. A detail sheet then opens for severity, notes or a corrected time, or you can ignore it.

## Tabs

- **Log:** the buttons, plus time since your last meal
- **History:** entries grouped by day. Filter them, tap one to edit or delete it, or copy them as plain text. **Doctor summary** gives counts, averages, medication results, possible patterns and a symptom log you can paste into a message.
- **Patterns:** weekly counts, the time of day symptoms happen, time since your last meal, food tags before symptoms compared with all your meals, and flags for coffee on an empty stomach, alcohol, short sleep, stress and late eating
- **More:** saved medications, the meal-to-symptom time window, backup and restore, sample data and the option to erase everything

## Install on iPhone

1. Host these files on any static HTTPS host (GitHub Pages works: Settings → Pages → deploy from this branch, root folder).
2. Open the URL in Safari, tap **Share** and then **Add to Home Screen**.

It works offline after the first load.

## Data

Everything is stored in the browser's `localStorage` on your device. Use **More → Copy backup** now and then, and restore by pasting the backup into **More → Restore**.

Patterns show what tends to come before symptoms in your own logs. They are not a diagnosis.
