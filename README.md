# Berlin District Picker - Telegram Mini App 2026

> **Pick Berlin Bezirke on an interactive map inside Telegram, then feed those choices into an apartment watcher bot.**

[![Platform](https://img.shields.io/badge/Platform-Telegram-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leonf83/tg-berlin-district-picker?style=flat-square)](https://github.com/leonf83/tg-berlin-district-picker)

---

<p align="center">
  <a href="https://leonf83.github.io/tg-berlin-district-picker/">
    <img src="https://img.shields.io/badge/Download-Berlin%20District%20Picker%20Latest-brightgreen?style=for-the-badge" alt="Download Berlin District Picker">
  </a>
</p>

> **[Direct Download - Berlin District Picker Latest](https://leonf83.github.io/tg-berlin-district-picker/)**

---

[Download Latest Build](https://leonf83.github.io/tg-berlin-district-picker/)

---

## What it is

Berlin District Picker is a Telegram Mini App built around a map of Berlin’s administrative districts (Bezirke). Instead of typing names from a plain list, you tap the areas you care about on the map.

The tool exists to support apartment watcher bots: you mark the parts of the city you want watched, then continue in the bot’s usual search flow. Because it runs as a Mini App, district choice stays inside Telegram rather than jumping to a separate desktop utility.

---

## What you get

- Clickable map covering Berlin’s districts
- Visual multi-select for Bezirke
- Native Telegram Mini App shell
- Intended pairing with an apartment watcher bot
- Search workflow centered on geography, not free-text labels
- Map UI as a stand-in for manual district typing
- Interface shipped as a browser-ready project build
- Small HTML-first application layout

---

## Getting it running

### Use the published build

Launch the current hosted Mini App from:

[Open Berlin District Picker](https://leonf83.github.io/tg-berlin-district-picker/)

It is meant to load in a normal browser and to be wired into a Telegram bot according to how you deploy the project.

### Work from a local clone

```bash
git clone https://github.com/leonf83/tg-berlin-district-picker.git
cd REPO
```

Serve the HTML assets over a local web server before opening them in a browser. For production, any static host that can serve the same files is enough.

---

## How to use it

1. Open the hosted build, or start the Mini App from Telegram.
2. Tap the district(s) you want on the map.
3. Confirm which Bezirk or Bezirke are active.
4. Resume the linked apartment watcher bot steps.
5. Reopen the map whenever your target area changes.

How selections move from the picker into the bot depends on your Telegram integration setup.

---

## Configuration notes

Focus stays on map selection and Telegram wiring. If the repo ships config-related files, inspect the HTML and companion assets for knobs before you deploy.

The public URL you host must match the Mini App URL registered on the bot side. Prefer editing project files for district behavior and UI options; there is no separate runtime config layer described for day-to-day tweaks.

---

## Requirements

- Telegram, when you use the Mini App path end to end
- A current browser, if you open the UI standalone
- Static hosting or a local HTTP server for the HTML app
- Network access for the hosted build and Telegram hooks
- An apartment watcher bot linked for the complete workflow

---

## FAQ

### How do I launch Berlin District Picker?

Open [Download Latest Build](https://leonf83.github.io/tg-berlin-district-picker/), or start the Mini App from the Telegram bot that embeds it.

### Are Berlin districts included?

Yes. The map is built for choosing Berlin Bezirke by click.

### Is this a full apartment listing product?

No. It only handles district selection for an apartment watcher bot. Listings and alerts stay with that bot.

### Can I revise my selection later?

Yes. Open the map again and pick the district set that matches your new search area.

### The app will not load — what next?

Check that the hosted URL responds, that your browser or Telegram client is up to date, and that the Mini App URL on the bot matches the deployment.

### How do updates show up?

Changes land in the repository and the hosted build. Prefer the newest package at [Download Latest Build](https://leonf83.github.io/tg-berlin-district-picker/).

### Where do settings live?

This is an HTML Mini App. Look through the repo and your deploy config for UI or integration options.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
