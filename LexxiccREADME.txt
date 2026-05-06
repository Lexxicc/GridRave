LexxiccREADME — GRIDRAVE
============================================
How my music background could improve this game.
Written: 2026-05-06
============================================

I know music theory and play a few instruments. GRIDRAVE is built around
rhythm and sound. Here is where that knowledge is actually useful.

--------------------------------------------
BPM AND FEEL
--------------------------------------------
The BPM climbs from 90 to 160 in fixed 8-BPM steps per level. Knowing
tempo families means I can tune this more intentionally:

  - 90 BPM = comfortable groove (hip-hop, mid-tempo house)
  - 120 BPM = classic house/dance — the natural sweet spot
  - 140 BPM = UK garage / early drum and bass territory
  - 160 BPM = pushing into hard techno / jungle

The jump increments could be non-linear — slower ramp early, steeper
toward the top — to match how difficulty is actually felt by a player.
Musical phrase awareness (4, 8, 16 bars) could also drive level transitions
so BPM changes land on a downbeat rather than mid-phrase, which sounds
cleaner and feels less jarring.

--------------------------------------------
PAD HIT SOUNDS — SCALE CHOICES
--------------------------------------------
Currently using a pentatonic scale for pad hit tones. Pentatonic is a
safe, consonant choice — nothing clashes. But knowing theory opens it up:

  - Dorian mode (minor with a raised 6th) — sounds darker but still groovy,
    common in electronic music
  - Phrygian dominant — exotic, tense, fits harder rave textures
  - Whole tone scale — every interval sounds equal, floaty and unsettling —
    good for the Beat Drop window
  - Chromatic cluster hits — random pitch from all 12 notes — chaotic,
    works well for danger pad punishment sound

I could also map the 4×4 grid spatially — each column = a different note,
each row = a different octave. Players would unconsciously play melodies
as they tap patterns. That is a design idea worth prototyping.

--------------------------------------------
RHYTHM AND SPAWN PATTERNS
--------------------------------------------
Right now pads spawn somewhat randomly on the beat. Knowing rhythm means
I can design intentional spawn patterns:

  - Syncopation — spawn pads on the off-beat (the "and" counts) to catch
    players out at higher levels
  - Polyrhythm — layer a 3-beat cycle inside a 4/4 grid, so some pads
    pulse against the main beat
  - Fills — every 4th or 8th bar, spawn a burst pattern (4 pads at once)
    to mirror a drum fill moment
  - Call and response — alternate active quadrants of the grid to create
    a left/right feel that matches musical phrasing

--------------------------------------------
THE BEAT DROP
--------------------------------------------
Currently fires every 30 seconds on a fixed timer. Musically that is
arbitrary — it can land anywhere mid-phrase.

Knowing phrase structure: the drop should land every 16 or 32 bars of
the current BPM. That way it always hits on a downbeat, which is exactly
where drops land in real EDM. The game would feel tighter without any
visible change to the design.

I could also grade the drop intensity:
  - Small drop (16-bar mark) — minor tempo spike, visual flash
  - Big drop (32-bar mark) — full Beat Drop as now, longer duration
  - Mega drop (64-bar mark, rare) — BPM jumps a full level, grid goes
    full-danger for 2 beats, then clears

--------------------------------------------
DYNAMICS AND VELOCITY
--------------------------------------------
Every pad hit currently plays at the same volume. On a real instrument,
velocity (how hard you hit) controls expression.

I could tie hit timing to volume: tap the pad early in its life window =
full velocity sound. Tap it late (near expiry) = quieter, slightly
detuned. This rewards early, confident taps and creates a more musical
feel without changing any game rules.

--------------------------------------------
CHORD MAPPING — LONGER TERM IDEA
--------------------------------------------
If the pad grid ever becomes chord-based rather than single-note:

  - Each row = a chord degree (I, IV, V, vi)
  - Tapping a full row simultaneously = a chord hit, bonus score
  - Combos that span multiple rows would naturally trace a chord
    progression

This would make GRIDRAVE feel less like a reflex game and more like an
instrument you are playing under pressure. That is a bigger redesign but
the bones are there for it.

--------------------------------------------
SUMMARY
--------------------------------------------
The biggest immediate wins:
  1. Phrase-locked Beat Drop timing (sounds tighter, zero visible change)
  2. Dorian or Phrygian scale for pad tones (darker, more rave-appropriate)
  3. Syncopated spawn patterns at higher levels (musically intentional
     difficulty, not just faster)

The bigger design idea worth exploring later:
  - Spatial note mapping on the grid (columns = notes, rows = octaves)

============================================
