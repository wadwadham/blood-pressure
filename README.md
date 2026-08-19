# Blood Pressure Log

A simple, private, single-file web app for logging daily blood pressure readings. No accounts, no server, no dependencies — your data stays in your browser.

## Features

- Log systolic, diastolic, and (optionally) pulse
- Running average over the last 7 days, 30 days, or all time
- Daily-average trend charts for systolic and diastolic, plotted over color-coded category zones (Low / Normal / Elevated / Stage 1 / Stage 2 / Crisis)
- Built-in reference chart of blood pressure categories (American Heart Association bands)
- Full history with per-reading category labels and one-tap delete
- Data is saved in your browser's localStorage and persists between visits

## Run it

Just open `index.html` in any browser. That's it — the whole app is one file.

## Host it on GitHub Pages

1. Create a new repository on GitHub (e.g. `bp-tracker`)
2. Upload `index.html` and this `README.md` (or push them with git)
3. In the repo, go to **Settings → Pages**
4. Under "Build and deployment", set Source to **Deploy from a branch**, pick the `main` branch and `/ (root)` folder, and save
5. After a minute, your app will be live at `https://<your-username>.github.io/bp-tracker/`

Open that URL on your phone and add it to your home screen for one-tap access.

## Notes

- Data is stored per browser/device. Readings logged on your phone won't appear on your laptop.
- Clearing your browser data will erase your log.
- On first launch the app seeds three example readings; delete them with the × if you don't want them.

## Disclaimer

For personal tracking only — not medical advice. Share your log with your doctor.
