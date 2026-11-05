# Echo Cavern

A free, original, single-file HTML5 exploration game: you are dropped into a
pitch-black cave and can only "see" with sound. Fire sonar pings, watch the
walls flash where the echo returns, and piece the cavern together in your mind.

## Play

Open `index.html` in any modern browser — desktop or mobile. No build step,
no external assets, no network required (the file runs fully offline).

## How it works

- **Sonar ping** (tap / `E`): an expanding wavefront paints wall outlines as
  glowing cyan line segments that fade out. Hold to charge a **strong ping**
  (wider radius, longer memory, 3x power cost).
- **Power economy**: pings cost power; standing still slowly recharges it.
  Run dry and you are walking blind.
- **Landmarks**: crystals chime a golden chorus from far beyond ping range —
  collect 3 to open the blue exit gate.
- **Hazards**: underground rivers and deep pits drag you back to the checkpoint;
  bat swarms wake when pinged and hunt you — stand still and they give up.
- **12 hand-designed caverns** (40×30 tiles each), progressive difficulty.

## Tech

Vanilla JavaScript, Canvas 2D, WebAudio (all graphics and sounds are
procedurally synthesized in-file). Portal SDKs load only on their own domains
(crazygames / gamedistribution); everywhere else the file is fully standalone.

## License

Original work. Free to play and distribute.
