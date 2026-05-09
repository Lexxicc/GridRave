# GRIDRAVE — Ruleset

> Keep this file in sync with the How to Play screen in `index.html` whenever rules change.

---

## The Grid

A 4×4 grid of pads lights up in time to the beat. Tap each lit pad in time to score.

---

## Run a Song

Each game plays one full track:

`INTRO → VERSE → BUILD → DROP → BREAK → BUILD → DROP → OUTRO`

The game ends when the song ends. **No lives** — just play through.

Pad density tracks the song:
- Sparse in intro and outro
- Building through verses
- Peak in the drops
- Breathing room in the breakdown

---

## Pad Types

| Pad | Behaviour |
|---|---|
| **Lit pad** | Tap in time to score. Combo +1 |
| **Pad with dot** (1 beat early) | Preview — not yet active. Early tap counts as full hit |
| **Danger pad** (red glow) | Trap. Do NOT tap. Tap = combo reset. Let it expire = nothing happens |
| **BREAK chord pad** (2-3 pads at once) | Hold all for 4 beats — release any = miss + combo break |

---

## Missed Beats

Miss a lit pad and it just fades. No life penalty, but:
- Combo breaks (back to ×1)
- The miss is added to your tally for the run

---

## Combo Multiplier

- Hit pads consecutively to build multiplier (×1 → ×5)
- Miss a pad or tap a danger pad — resets to ×1

---

## Scoring

- Each hit = **10 pts × current multiplier**
- Max combo hit = **50 pts**
- BREAK chord = **25 × pads × combo**
- Final accuracy = `hits / (hits + missed)`

---

## Tracks

| Track | Artist | Style |
|---|---|---|
| HELIOS | NXVØS | Big-room |
| SUBTERRANEAN | KILO ZERO | Melodic dubstep |
| NEON HEART | RUBY OKTANE | Synthwave |
| TRENCH | VOID SECTOR | Driving techno |
| SUNDIAL | AURA-9 | Progressive house |

Each has its own drum kit, bassline, lead synth, and 32-bar phrase structure.

User-imported MP3 tracks also supported — drop into Discography.

---

## Discography

Replaces classic Track Select.

- Playlist-style list of all available tracks
- Tap **▶** for an 8-bar preview (drops into the hook)
- Tap a row to select for next run
- **RANDOM** picks one for you
- Animated equaliser shows currently previewing track

---

## Game History

- Per-track tabs (ALL + one tab per track)
- Default-active = last-played
- Up to 25 runs per track

---

Last updated: 2026-05-09 — v0.0.16
