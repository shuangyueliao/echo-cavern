# Echo Cavern — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

The cave is pitch black — you can't see a thing. Tap to send a sonar ping and
watch the walls flash where the echo returns, then fade. Piece the cavern
together from fading echoes, collect 3 crystals to open the exit gate, and
don't wake the bats. 12 handcrafted caverns.

(196 characters)

## Details

- Genre: Exploration / Puzzle / Atmospheric
- Controls: Keyboard WASD / arrows + E or Space to ping (hold to charge a
  strong ping), or mouse click. Touch: left-side virtual stick to move,
  right-side PING button (hold to charge).
- Features:
  - Sonar vision — walls reveal as glowing echo line segments that fade
  - Power management — pings cost power, standing still recharges it
  - Crystal chorus — crystals chime gold from far beyond ping radius as
    directional landmarks
  - Bat stealth — pings wake bat swarms; freeze and they give up
  - Rivers and pits drag you back to the checkpoint
  - 12 hand-designed levels (40x30 tiles), progressive difficulty
  - Per-level best scores saved locally
  - Procedural graphics and WebAudio-synthesized sound (delayed echo returns,
    crystal chords, bat screeches, river ambience)
- Tech: Vanilla JavaScript, Canvas 2D, WebAudio. Single-file HTML5, zero
  external assets, no analytics, no external links, works offline once loaded.

## Tags

sonar, echo, cave, exploration, dark, stealth, puzzle, atmospheric,
single-file, maze

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / happytime events wired (loadingStart /
      loadingStop handled by the domain-guarded loader)
- [x] Responsive (canvas fills window, camera follows player, portrait and
      landscape OK)
- [x] Touch controls (virtual joystick + PING button) and desktop input
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280x720)
- [ ] Screenshots: screenshot-raw.png (1280x800)

## GameDistribution
- Upload echo-cavern-gd.zip (contains index.html only)
- Orientation: any (canvas adapts); genre: Puzzle/Adventure

## itch.io
- Upload echo-cavern-itch.zip, mark "This file is playable in browser",
  entry file: index.html, kind: html. Recommended viewport: fill window.
- Pricing: $0 (donations optional)
