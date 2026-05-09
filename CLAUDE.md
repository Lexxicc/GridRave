# GRIDRAVE

**Code:** GR
**Remote:** https://github.com/Lexxicc/GridRave
**Version:** v0.0.16 (in `index.html` footer)
**Genre:** Rhythm / pad tap game

## Tech
- DOM grid + Web Audio API
- Vanilla JS + Tailwind CSS via CDN
- Single-file HTML — no build step
- OPW (One Prompt Wonder) shell
- MP3 loader for full-song tracks

## localStorage
- `GR_stats` — per-track history (ALL + per-track tabs, 25-runs cap)
- `WIPE_PLAYER_HISTORY` — wipe-flag honoured cross-game

## Notes
- Beta-five focus game (alongside DS, FB, BJ, FF)
- 5 default tracks: HELIOS, SUBTERRANEAN, NEON HEART, TRENCH, SUNDIAL
- Each track has own BPM + section structure (INTRO → VERSE → BUILD → DROP → BREAK → BUILD → DROP → OUTRO)
- 4×4 pad grid, beat-anchored hit detection
- BREAK chord-hold mechanic (2-3 pads, 4-beat hold, progress bar)
- Bass-only intro for first ~4 bars across all default songs (clean silence before bass enters)
- AudioContext resume retry for iOS/Safari
- Pad-hit chime constrained to song's current chord (no discordant notes)
