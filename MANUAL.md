# ChopPad manual

For version 0.36.0. ChopPad is laid out like a hardware pad sampler: one main screen with three keys above it (B1–B3) and three knobs below it (K1–K3), a DATA WHEEL, a FADER, and 16 pads. Everything happens on the one screen: recording, kits, chopping and the song list are pages of it, not separate windows.

## The layout

**iPhone, portrait** (top to bottom):

- The **FADER** on the left of the screen. **B1–B3** above the screen choose what the screen's page shows; their names change with the page.
- On the right of the screen: **SAMPLE SELECT**, **TAP TEMPO**, the **DATA WHEEL** and **− / +**.
- **MODE keys** (SAMPLE, SEQ, PAD FX, KNOB FX), the knobs **K1–K3**, and the **PAD PLAY keys** (CHOP, MUTE, LOOP, 16 LEVELS).
- **SHIFT, PAD BANK, ERASE, NOTE REPEAT**.
- **SAMPLE RECORD, SEQ RECORD, STOP, PLAY**.
- The **16 pads**, square, across the full width, numbered 1–16 from the bottom left.

**iPhone, landscape** (with the notch on the left): SHIFT, PAD BANK, the FADER, ERASE and NOTE REPEAT run down the left edge, the screen with everything around it is in the middle, and the pads fill the right side from top to bottom.

**iPad**: the same keys, arranged to fill the bigger screen with square pads. Portrait: the screen, keys and knobs across the top, then SHIFT, PAD BANK, the FADER, ERASE and NOTE REPEAT down the left of the pads. Landscape: the pads fill the right side top to bottom; on the left the screen with the FADER beside it, then SAMPLE SELECT, TAP TEMPO, the wheel and − / +, the MODE keys, knobs and PAD PLAY keys, the SHIFT row and the transport row. The status bar is hidden on iPad.

Keys react as soon as you touch them, like real buttons, and you can hold several keys and pads at once. Messages about what just happened (for example "COPIED A1 → A2") appear for a moment in the middle of the screen.

## Quick start: your first beat

1. Tap a few pads. Bank A has a drum kit: kick on pad 1, snare on 2, hi-hats on 3 and 4.
2. Press **SEQ**. Hold **B1** and turn the wheel to set the tempo, or tap the big BPM number to type it.
3. Press **SEQ RECORD** (it blinks: ChopPad is waiting), then **PLAY**. After a one-bar count-in it records. Play the pads in time with the click.
4. The loop goes round; every pass you can add more. Press **SEQ RECORD** again to stop recording and keep listening.
5. Made a mistake? **SHIFT + −** is UNDO. Press **STOP** to stop.

Your work saves itself. To keep a copy under a name, open your kits (see below).

## Pads and banks

- **Hit a pad** to play it. It also becomes the *selected pad*: the SAMPLE screen and the knobs work on it. **Hold SAMPLE and hit a pad** to select it without hearing it.
- **8 banks, A to H**, of 16 pads each. Tap **PAD BANK** for the next bank, **SHIFT + PAD BANK** for the one before, or hold PAD BANK and hit pads 1–8 to jump to bank A–H.
- **ERASE + pad**: while the sequence plays, or on the SEQ screen, it erases that pad's notes and keeps its sound; otherwise it empties the pad. Tap ERASE on its own and it stays on (it reads **DONE**); tap it again when you're finished.
- **COPY** (SHIFT + ERASE): hit the pad to copy from, then the pad to copy to. Tap **DONE** when you're finished.
- **Hold a pad during playback** (not while recording) to mute its recorded part while you hold it.

## Every key

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
| MIX | LEVEL | REVERB (SHIFT: KIT VOL) | PAN |
| AMP | ATTACK | DECAY | RELEASE |
| TUNE | SEMI (±24, pitch only, the length stays) | FINE (±90 cents) | WARP (beats to the tempo, by pitch or time stretch) |
| PLAY | POLY / MONO | MUTE GROUP | PAD LINK (SHIFT + knob: link offset) |
| FILTER | CUTOFF | RESO | TYPE |
| F-ENV | ATTACK | DECAY | DEPTH |

With SHIFT held on the SAMPLE screen: **B1 LOOP LOCK** (the loop goes back to START) and **B3 NORMALIZE**.

The switches beside the pad's name (NOTE ON, REV, LOOP, 16) can be tapped to turn them on or off. They do the same as SHIFT + CHOP, SHIFT + LOOP, LOOP and 16 LEVELS. LEVEL and PAN (knob or fader) change a sound while it's playing.

## Loading a sound

1. Select a pad and press **SAMPLE SELECT**.
2. The pad the sound will go to stays lit. Pick a folder (DRUMS, KEYS, RECORDS, MINE, SONGS) and a sound. **B2 FILES** opens the Files app, and **B1 BACK** goes up a folder.
3. The sound goes onto the selected pad.

To save the trimmed part of a pad as its own sample, press **SHIFT + SAMPLE SELECT** (SAVE SAMPLE), name it, then press **B3 DO IT**. It goes into MINE.

## Picking the part of a song

A song longer than 30 seconds (from SONGS or FILES) opens in **PICK PART** first, so you can choose the part to sample before chopping.

1. Press **PLAY** to listen; the white line is the playhead. Turn the wheel or tap the waveform to move it.
2. Press **B1 START HERE** and **B2 END HERE** at the playhead, or set **K1 START** and **K2 END** directly. **K3 MOVE** slides the whole part along the song.
3. To zoom in, hold SHIFT and turn the wheel (around the playhead), pinch the waveform, or hold SHIFT and turn K1, K2 or K3 to zoom around START, END or the playhead. Drag sideways to scroll while zoomed, and tap **ALL** to see the whole song again. The wheel moves the playhead in finer steps the closer you zoom.
4. Press **B3 CHOP IT**. Only that part opens in CHOP, and only that part is saved when you put it on the pads.

Shorter sounds go straight onto the selected pad.

## Chopping

1. Select a pad with a sound (or an empty pad, then pick a song) and press **CHOP**.
2. It opens in MANUAL, ready to chop live on the pads (see below). Turn **K3** for another type: THRESHOLD (at every hit), REGIONS 4 / 8 / 16 (even slices) or MANUAL.
3. Tap a pad to hear its slice. **B1 EXTRACT** copies the selected slice to the first empty pad, **B2 SPLIT** cuts it in two, and **B3 MERGE** joins it with the next. Hold ERASE and tap a pad to remove that slice.
4. Tap **→ PADS** to put every slice on the pads of the current bank, from pad 1 up (in MANUAL, from the first pad you hit). This replaces what's on those pads.

**MANUAL (lazy chop):**
1. Turn the wheel to move the playhead (the white line) to where the first slice should start. Hold SHIFT for finer steps. You can also tap the waveform.
2. Hit a pad: slice 1 starts there and the sample starts playing.
3. Hit the next pads up, in order, wherever new slices should start (e.g. 13, 14, 15, 16).
4. Press **STOP**, then tap **→ PADS**. Each slice goes on the pad you hit for it.

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

Press **SAMPLE RECORD**. The knobs set it up:

- **K1 SOURCE**: the mic (or a plugged-in mic or audio interface), or RESAMPLE, which records what ChopPad itself plays.
- **K2 LENGTH**: free (until you stop) or exactly the length of the sequence, in time with it.
- **K3 THRESHOLD**: start straight away, or wait until the sound is loud enough.
- **B1 MONITOR**: hear the input while recording (off, auto, on).

Tap a pad to record onto it. While it records, other pads chop the take as you go; tap the first pad again, STOP or SAMPLE RECORD to stop.

**SAMPLE RECALL** (SHIFT + SAMPLE RECORD): ChopPad always keeps the last 30 seconds of what came out of it. If you just played something good without recording, this puts it on the first empty pad.


## Kits (projects)

A kit is everything: all 8 banks with their settings, the 128 sequences, the song and the effects. Your own recordings and samples are saved with it.

Open your kits with **SHIFT + pad 16** (PROJECT) or by tapping the kit's name on the screen. Type a name and tap **SAVE**, load a saved kit, or start from a factory kit: **Default**, **Soul Session**, **Jazz Club**, **Keys & Strings** and **Organ Trio**. **B2 ABOUT** (or ABOUT on the kits page) shows the version and credits.

**UNDO and REDO** (SHIFT + − and SHIFT + +) take back and redo the last changes: recordings, erases, copies, loaded sounds, edits. On the CHOP screen they undo chop changes.

## What's different from a hardware sampler

- **No pressure on the pads.** Glass can't feel how hard you hit, so pads play at full level. Use 16 LEVELS VELOCITY for soft and loud hits.
- **Not on ChopPad:** MIDI, computer connection and firmware updates.
- **Extras:** sampling songs straight from your music library, the built-in instruments and the ChopPad Records (four old soul and jazz tunes made to be chopped).
