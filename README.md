# Perihelion

An orrery that sings. Open `index.html` in a browser, press **Listen**, and play.

Worlds orbit a star on true Keplerian ellipses. Each one sounds a note every time it
passes perihelion, its closest point to the star.

- **Tap** the plate to set a world in a circular orbit.
- **Drag** to fling one. The dashed preview shows the orbit, note and rhythm you will get.
- **Tap a world** to remove it.
- The **angle** of the perihelion picks the note (the rim is a circular keyboard).
- The **distance** sets the rhythm. Kepler's third law does the rest: small orbits are
  fast and high, wide orbits are slow and deep.
- Eccentric orbits answer at aphelion, an octave lower.
- Fling too hard and you get a **comet** that strums every ring on its way out.
  Too soft and the world falls into the star.
- **Star mass** is the tempo: a heavier star makes everything orbit faster.
- **In resonance** snaps periods to whole ratios so the system loops. **Free** lets
  orbits drift in and out of phase.

Three systems ship with it:

| System | What it is |
| --- | --- |
| Harmonices | A composed nine-world system that repeats every 48 beats. |
| TRAPPIST-1 | The seven known planets, with their true period ratios, a near-resonant chain. |
| Sol's inner worlds | Mercury to Ceres with true periods, eccentricities and longitudes of perihelion, so each note is set by where the real perihelion points. |

Everything is one self-contained file: canvas for the plate, Web Audio for the four
synthesised voices, reverb and echo. No build step, no dependencies.
