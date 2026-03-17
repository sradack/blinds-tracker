# Poker Tournament Tracker

Single-file poker tournament blind timer for display on a TV or projector.

**Live:** https://sradack.github.io/blinds-tracker/

## Features

- Countdown timer per blind level with pause/resume
- Auto-generates blind structures from stack size, player count, and number of levels
- Blind values snap to standard poker denominations (25, 50, 75, 100, 150, 200, 300…)
- Starting stack chip breakdown display
- Configurable chip denominations with color coding
- Blind level skyscraper sidebar with current level highlighted
- Wall clock display
- Audio alerts at warning threshold and level end
- Fullscreen support
- All settings persisted to localStorage

## Usage

Open `index.html` in a browser. No build step, no dependencies, no server required.

Use the **⚙ Settings** button to configure:
- Tournament name and start time
- Blind levels (manual or auto-generated)
- Chip denominations
- Warning alert threshold

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Start / Pause / Resume |
| `←` `→` | Previous / Next level |
| `F` | Toggle fullscreen |
