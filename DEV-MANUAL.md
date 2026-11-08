# ChopPad Dev: manual

ChopPad Dev is the experimental build. It's laid out like a hardware pad sampler: one main screen, three keys above it (B1–B3), three knobs below it (K1–K3), a DATA WHEEL, a fader, and the 16 pads. It installs next to the normal ChopPad with its own separate data.

Every key has a second job printed under it in orange. Hold **SHIFT** (or tap it once to latch it) and press the key to use that second job. With SHIFT on, the pads show their SHIFT jobs too.

## The panel

| Key | Press | SHIFT + key |
|---|---|---|
| SAMPLE | Sample screen (hold SAMPLE + pad to select a pad without playing it) | INPUT CONFIG (recording) |
| SEQ | Sequence screen | STEP EDIT |
| PAD FX | Performance effects on the pads | FLEX BEAT |
| KNOB FX | Knob effect screen | FX SELECT (next effect) |
| CHOP | Chop the selected pad's sound (an empty pad opens SONGS) | NOTE ON (pad plays only while held) |
| MUTE | Pads mute their sounds | UNMUTE ALL |
| LOOP | Loop the selected pad | REVERSE |
| 16 LEVELS | One sound across all 16 pads | TYPE (tune, velocity, filter) |
| PAD BANK | Next bank (hold it and hit pads 1–8 for banks A–H) | Previous bank |
| ERASE | Hold + pad: erase the pad's notes (playing) or its sound (stopped). A tap keeps it on. | COPY (first pad = from, next pad = to) |
| NOTE REPEAT | Hold with pads to roll; a tap keeps it on | TRIPLET |
| SAMPLE SELECT | Sounds to load onto the selected pad | SAVE SAMPLE |
| TAP TEMPO | Tap the tempo (hold it and turn the wheel to set the BPM) | METRONOME off / on / record only |
| − / + | Previous / next pad or value | UNDO / REDO |
| SAMPLE RECORD | Record from the mic or resample | SAMPLE RECALL (the last 30 s you played) |
| SEQ RECORD | Record pad hits into the sequence | SEQ RECALL (what you just played goes in) |
| STOP | Stop; press again to silence everything | |
| PLAY | Play from the start (on the CHOP screen: play the sample) | CONTINUE from where it stopped |

**DATA WHEEL:** turns the selected knob (the one with the outline); press it to select the next knob. SHIFT + wheel zooms on TRIM. On the SEQ screen it moves the playhead, in SAMPLE SELECT it scrolls the list, and in MANUAL chop it moves the chop playhead.

**Knobs:** drag up/right to turn up and down/left to turn down. Double-tap a knob to reset it, and tap a number with an underline to type it in.

## SAMPLE screen

B1–B3 pick the knob page; press a B key again to go to the next page in its group.

| Page | K1 | K2 | K3 |
|---|---|---|---|
| TRIM | START | END | LOOP point (fully left = LOOP LOCK) |
| MIX | LEVEL | KIT VOL | PAN |
| AMP | ATTACK | DECAY | RELEASE |
| TUNE | SEMI (±24) | FINE (±90 cents) | WARP (beats to the tempo, by pitch or time stretch) |
| PLAY | POLY / MONO | MUTE GROUP | PAD LINK (SHIFT + knob: link offset) |
| FILTER | CUTOFF | RESO | TYPE |
| F-ENV | ATTACK | DECAY | DEPTH |

With SHIFT held on the SAMPLE screen: **B1 LOOP LOCK** (the loop goes back to START) and **B3 NORMALIZE**.

## Loading a sound

1. Select a pad and press **SAMPLE SELECT**.
2. Pick a folder (DRUMS, KEYS, RECORDS, MINE, SONGS) and a sound. **B2 FILES** opens the Files app, and **B1 BACK** goes up a folder.
3. The sound goes onto the selected pad.

To save the trimmed part of a pad as its own sample, press **SHIFT + SAMPLE SELECT** (SAVE SAMPLE), name it, then press **B3 DO IT**. It goes into MINE.

## Chopping

1. Select a pad with a sound (or an empty pad, then pick a song) and press **CHOP**.
2. Turn **K1** to choose how to chop: THRESHOLD (at every hit), REGIONS 4 / 8 / 16 (even slices) or MANUAL.
3. Tap a pad to hear its slice. **B1 EXTRACT** copies the selected slice to the first empty pad, **B2 SPLIT** cuts it in two, and **B3 MERGE** joins it with the next. Hold ERASE and tap a pad to remove that slice.
4. Tap **→ PADS** to put every slice on the pads of the current bank, from pad 1 up. This replaces what's on those pads.

**MANUAL (lazy chop):**
1. Turn the wheel to move the playhead (the white line) to where the first slice should start. Hold SHIFT for finer steps. You can also tap the waveform.
2. Hit a pad: slice 1 starts there.
3. Press **PLAY**. The sample plays from the playhead.
4. Hit the next pads in order wherever new slices should start.
5. Press **STOP**, then tap **→ PADS**.

If you're late on a hit, tap that pad again while it plays: it jumps back to that slice's start. **SHIFT + −** undoes the last chop change, and **SHIFT + +** redoes it.

## SEQ screen

- **K1** BARS (1–128), **K2** Q (the grid notes snap to), **K3** SWING.
- **B1** hold and turn the wheel to set the BPM, or tap the big BPM number to type it. **B3** turns REC QUANTIZE on or off.
- **SEQ RECORD** then **PLAY** records with a count-in (if it's on). Pads with recorded notes act as mute switches while the sequence plays.
- The chips on the screen set the time signature, metronome, pads picking sequences, song mode, resample, and erase all.

**STEP EDIT (SHIFT + SEQ):** pads turn notes on or off on the current step, and the wheel moves between steps. B1/B2 nudge the note and B3 deletes it. With SEQ RECORD armed, each pad hit adds a note and moves to the next step.

**NOTE REPEAT:** while it's on, B1–B3 pick 1/8, 1/16 and 1/32 (with SHIFT: the triplets).

## SHIFT + pads

| Pad | Job |
|---|---|
| 1 | (empty: the pads are always full level) |
| 2 | HALF SEQ: half the bars |
| 3 | DOUBLE SEQ: twice the bars, notes copied (up to 128) |
| 4 | COUNT IN on or off |
| 5 | COMPRESSOR on or off |
| 6 | HALF SPEED: the notes play half as fast (the tempo stays) |
| 7 | DOUBLE SPEED: the notes play twice as fast |
| 8 | TAKEOVER: how the fader picks up a value (pickup, scaled, instant) |
| 9 | FADER: what the fader controls |
| 10 | REC QUANTIZE on or off |
| 11 | RESAMPLE: the sequence (or song) onto the first empty pad |
| 12 | SONG mode |
| 13 | TRIM: cut the sample down to START and END |
| 14 | TIME CORRECT: snap the recorded notes to Q |
| 15 | WARP: switch between time stretch and pitch |
| 16 | PROJECT: save and load kits |

## Effects

- **PAD FX:** hold a pad to play its effect over the whole beat. B1 LATCH keeps it on. **FLEX BEAT** (SHIFT + PAD FX) swaps the effects for beat-repeat style ones, with B2 ONE SHOT / LOOP and B3 QUANTIZE.
- **KNOB FX:** one effect at a time (vintage, vinyl, tape, delay, filter, pump, compressor). The wheel or SHIFT + KNOB FX picks it, K1–K3 set it, and B2 sets whether it's on all pads or only the pads you tap.

## Recording sounds

Press **SAMPLE RECORD**, choose the source and threshold, then record. Pads route the take onto the pad you pick. **B1** sets the MONITOR (off, auto, on).
