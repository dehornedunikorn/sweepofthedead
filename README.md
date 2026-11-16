# SWEEP OF THE DEAD

A mobile-friendly zombie survival puzzle inspired by classic minesweeper logic and post-apocalyptic survival fiction.

## Play
Open `index.html` in a browser. No build step, dependencies, account, or paid assets required.

## Current prototype
- 10×10 procedurally generated map
- Hidden infected, loot caches, and an exit
- Adjacent-threat numbers and flag mode
- Health, ammunition, food, and bandages
- Combat resolution, loot rewards, win/lose states
- Responsive desktop and touch layout

## Controls
- Tap/click a tile to explore
- Toggle **Flag mode** to mark suspected danger
- Use a bandage to restore one health point
- Find the exit before losing all health

## Art direction
Original compact pixel-art / illustrated survival UI. The current prototype draws its board and interface with native HTML/CSS and emoji glyphs, so it has no external asset dependencies. The dedicated sprite-sheet is tracked separately in `assets/ASSET_SHEET.md`.

## Roadmap
1. Replace placeholder glyphs with a consistent production sprite atlas
2. Add persistent survivor progression and multiple districts
3. Add survivor encounters, crafting, barricades, and sound
4. Add difficulty scaling and save data
