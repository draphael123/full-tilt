# FULL TILT

A 3D horse-racing joust-brawler. Race five rival knights around a castle-grounds
circuit — and unhorse them with your lance on the way.

**The name is the pitch:** "full tilt" means both top speed and a jousting pass.
Damage scales with closing speed, so racing skill and fighting skill are the same skill.

## How it plays

- **Momentum riding** — your horse builds gallop *gears* while riding clean.
  Heavy, committed drifts (hold SHIFT) keep your speed through corners; a long
  slide releases into a burst of speed and a stamina kickback.
- **Aimed lance combat** — near a rival, strike one of three zones:
  **HIGH** (helm — big damage, unhorses outright on a fast pass),
  **MID** (shield — reliable, but blockable), **LOW** (mount — breaks their gear).
- **Read their guard** — 🛡️ shield blocks MID (and staggers you), ⬇️ duck evades
  HIGH, 〰️ weave evades LOW. Strike the zone they leave open.
- **Stamina gates aggression** — strikes cost stamina; it only regenerates while
  riding clean. Commit to a pass, spend the bar, then race to earn the next one.
- **The tilt lane** — each lap the dogbone circuit funnels outbound and returning
  riders down opposite sides of a wooden barrier. Head-on passes have the highest
  closing speed in the game: land a clean HIGH strike there and they're in the dirt.
- **Kart-hit unhorsing** — empty a health bar and that knight ragdolls off, remounting
  a few seconds later at gear 1. Races stay close; nobody is ever safe.

## Controls

| Key | Action |
| --- | --- |
| W / S | gallop / brake + duck |
| A / D | steer |
| SHIFT (hold) | drift |
| I / O / P | lance strike HIGH / MID / LOW |
| SPACE | raise shield (blocks MID) |
| M / R | mute / restart |

## Tech

Single-file Three.js (`index.html`), no build step. Serve statically:

```
python -m http.server 5723 -d .
```

Built with [Claude Code](https://claude.com/claude-code).
