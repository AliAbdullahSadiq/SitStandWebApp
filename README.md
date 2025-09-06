# Sit-Stand Desk Reminder

A simple, self-hosted web app that reminds you to alternate between sitting and standing at your desk. Fully customizable timers let you set your preferred sit and stand durations, and you can add your own alert sounds. Runs entirely in the browser — no server required. Perfect for improving posture and staying active while working.

## Features
- Customizable sit and stand intervals
- Infinite looping between sitting and standing periods
- Supports your own alert sounds (`sit.mp3` / `stand.mp3`)
- Lightweight and self-contained (HTML + JavaScript + CSS)
- Works offline — just open in any browser

## Usage
1. Clone or download this repository to a folder, e.g., `SitStandWebApp/`.
2. Obtain your own sound effects for sit and stand reminders. Rename them to `sit.mp3` and `stand.mp3`.
3. Place `sit.mp3` and `stand.mp3` in the same folder as `index.html`.
4. Open `index.html` in your preferred web browser.
5. Set your desired sit and stand durations (in minutes) and click **Start**. (Default is 50 mins sit and 10 mins stand)
6. The app will loop between sitting and standing, playing your alert sounds at each interval.

**Note:** This repository does not include sound files due to licensing. Users must provide their own `sit.mp3` and `stand.mp3` in the same folder as `index.html`. You can find free sound effects from sites like [freesound.org](https://freesound.org/) or [pixabay.com/sound-effects](https://pixabay.com/sound-effects/).
