# ChopPad manual

For version 0.20.0. ChopPad is laid out like the Akai MPC Sample: the same keys, with the same names, in the same groups. If you know that machine you already know most of this app; if you don't, this manual walks through everything.

**Contents**

1. [The layout](#1-the-layout)
2. [Quick start: your first beat](#2-quick-start-your-first-beat)
3. [Pads and banks](#3-pads-and-banks)
4. [SHIFT](#4-shift)
5. [The SAMPLE screen](#5-the-sample-screen)
6. [Loading sounds: SAMPLE SELECT](#6-loading-sounds-sample-select)
7. [Chopping: CHOP](#7-chopping-chop)
8. [Recording sounds: SAMPLE RECORD](#8-recording-sounds-sample-record)
9. [The sequencer: SEQ](#9-the-sequencer-seq)
10. [Pad play keys: MUTE, LOOP, 16 LEVELS](#10-pad-play-keys-mute-loop-16-levels)
11. [Effects: PAD FX and KNOB FX](#11-effects-pad-fx-and-knob-fx)
12. [Kits (projects)](#12-kits-projects)
13. [Every key at a glance](#13-every-key-at-a-glance)
14. [What's different from the MPC Sample](#14-whats-different-from-the-mpc-sample)

---

## 1. The layout

From top to bottom (in landscape, the screen and keys sit on the left and the pads on the right):

- **The screen.** It shows one of five pages: SAMPLE, SELECT, SEQ, PAD FX or KNOB FX. The kit's name is in the top right corner; tap it to open your kits.
- **MODE keys** (left of the knobs): **SAMPLE**, **SEQ**, **PAD FX**, **KNOB FX**. They choose the screen page.
- **K1, K2, K3**: three knobs. What they change depends on the page; the label under each knob says what it does. Drag up/down to turn a knob, double-tap it to reset it, and tap the number to type a value in.
- **PAD PLAY keys** (right of the knobs): **CHOP**, **MUTE**, **LOOP**, **16 LEVELS**.
- **Two rows of keys**:
  - **SHIFT, PAD BANK, ERASE, NOTE REPEAT, −, +**
  - **SAMPLE SELECT, TAP TEMPO, SAMPLE RECORD, SEQ RECORD, STOP, PLAY**
- **16 pads**, numbered 1 to 16 from the bottom left, like an MPC.

Keys react as soon as you touch them, like real buttons. Many keys have a second job, which you get with SHIFT (see [section 4](#4-shift)).

## 2. Quick start: your first beat

1. Tap a few pads. Bank A has a drum kit on it: kick on pad 1, snare on 2, hi-hats on 3 and 4.
2. Press **SEQ** to see the sequencer. Turn **K1** (BPM) to set the tempo.
3. Press **SEQ RECORD**. It blinks: ChopPad is waiting for you.
4. Press **PLAY**. After a one-bar count-in it starts recording. Play the pads in time with the click.
5. The loop goes round and round; every pass you can add more. Press **SEQ RECORD** again to stop recording and keep listening.
6. Made a mistake? **SHIFT + −** is UNDO.
7. Press **STOP** to stop.

Your work saves itself. To keep a copy under a name, use **SHIFT + SAMPLE SELECT** (SAVE).

## 3. Pads and banks

- **Hit a pad** to play it. That pad also becomes the *selected pad*: the SAMPLE screen and the knobs work on it.
- **Hold SAMPLE and hit a pad** to select it without hearing it.
- **− and +** select the pad before or after.
- There are **8 banks, A to H**, of 16 pads each: 128 pads in all.
  - **Tap PAD BANK** to go to the next bank.
  - **Hold PAD BANK and hit pads 1 to 8** to jump straight to bank A to H. While you hold it, the pads show the bank letters.
  - **SHIFT + PAD BANK** goes to the bank before.
- **ERASE + pad**: hold ERASE and hit a pad. While the sequence plays, it erases that pad's notes from the sequence. When stopped, it removes the pad's sound. Tap ERASE once quickly to keep it on, and tap it again when you're done.
- **COPY** (SHIFT + ERASE): hit the pad to copy from, then the pad to copy to.
- **Hold a pad during playback** (not while recording) to mute its recorded part for as long as you hold it.

## 4. SHIFT

**Hold SHIFT** and press another key or pad, or **tap SHIFT once** and the next key or pad you press uses its SHIFT job. While SHIFT is on, every key shows its second job in orange and the pads show theirs.

**SHIFT + pads** (the jobs printed under the MPC Sample's pads):

| Pad | Job | What it does |
| --- | --- | --- |
| 1 | FULL LEVEL | Touch pads always play at full level, so this just tells you so |
| 2 | HALF SEQ | Halves the sequence length; notes past the new end go |
| 3 | DOUBLE SEQ | Doubles the length and copies the notes into the new half |
| 4 | COUNT IN | Count-in before recording, on or off |
| 5 | COMPRESSOR | Turns the KNOB FX compressor on or off |
| 6 | HALF SPEED | Halves the tempo |
| 7 | DOUBLE SPEED | Doubles the tempo |
| 8 | MIDI | Not available |
| 9 | FADER | Not available; use the knobs |
| 10 | QUANTIZE | Moves the recorded notes onto the TIME CORRECT grid |
| 11 | RESAMPLE | Records the sequence (or song) onto the first empty pad |
| 12 | SONG | Song mode on or off (see [section 9](#9-the-sequencer-seq)) |
| 13 | TRIM | Cuts the selected sound down to its START and END |
| 14 | TIME CORRECT | Steps through the timing grid (OFF, 1/8, 1/16, 1/32) |
| 15 | WARP | Makes the selected sound follow the tempo (see [TUNE](#tune)) |
| 16 | PROJECT | Opens your kits |

The SHIFT jobs of the keys are listed in [section 13](#13-every-key-at-a-glance).

## 5. The SAMPLE screen

Press **SAMPLE**. The screen shows the selected pad's name and waveform, and a playhead while it plays. **Tap the waveform** to open the trim view: zoom with two fingers, drag the start and end, rename the pad, reverse it, choose a mute group.

Along the bottom are five pages, as on the MPC Sample. Each one sets what K1, K2 and K3 do:

### TRIM
- **START** and **END**: which part of the sound plays.
- **LOOP**: where a looping pad jumps back to. Turned fully left it shows **LOCK**: the loop goes back to START.

### MIX
- **LEVEL**: volume.
- **PAN**: left or right.
- **REVERB**: how much of the pad goes into the reverb.

### AMP
- **ATTACK**: fades the sound in.
- **DECAY**: fades it out. The switch above the pages chooses whether the fade runs from the **end** of the sound (the MPC's normal way) or from the **start**. You can also drag the A and D handles on the waveform.
- **RELEASE**: the fade after you let go of the pad. It only works when the pad plays **NOTE ON** (while held), so turning it up switches a **ONE SHOT** pad to NOTE ON. The second switch changes this by hand.

### TUNE
- **SEMI**: pitch in semitones (±24).
- **FINE**: pitch in cents (±50).
- **WARP**: the sound follows the sequence tempo. Set how many beats long the sound is (1 to 64) and ChopPad changes its speed to fit the BPM; change the tempo and the sound follows. As on a classic sampler, faster means higher pitch. While WARP is on, SEMI and FINE are greyed out. **SHIFT + pad 15** turns WARP on and guesses the number of beats for you.

### FILTER
- **TYPE**: OFF, CLASSIC (the MPC low-pass), LP 2, LP 4 (low-pass), HP 2, HP 4 (high-pass), BP 2, BP 4 (band-pass). 2 is gentle, 4 is steep.
- **CUTOFF**: where the filter cuts.
- **RESO**: resonance, a peak at the cutoff.

All of these work live: turn them while the pad plays.

## 6. Loading sounds: SAMPLE SELECT

Press **SAMPLE SELECT**. The screen lists sounds in four tabs:

- **DRUMS**: the built-in drum sounds.
- **KEYS**: instruments and chords (e-piano, organ, vibes, bass, strings, brass).
- **RECORDS**: four old soul and jazz tunes made for ChopPad, to chop.
- **MINE**: your own samples and recordings.

Tap a sound to hear it, then hit the pad it should go on. Press SAMPLE SELECT again to go back.

## 7. Chopping: CHOP

**CHOP** opens the chop screen with the selected pad's sound. On an empty pad, it opens it so you can pick a song.

1. **Pick a song** from your music library (songs stored on the device, not Apple Music streams) or from the Files app, or one of the ChopPad Records. Press ▶ in the list to listen first.
2. **PITCH**: make the song higher or lower without changing its speed.
3. **Choose the part** to chop, with START and END. Pinch to zoom, drag to scroll. **LOOP** repeats it so you can hear if it loops cleanly.
4. **Chop it** in one of these ways:
   - **Regions**: even slices.
   - **Threshold**: a slice at every hit.
   - **Manual**: place the markers yourself; select a slice to SPLIT, MERGE or nudge it.
   - **TAP CHOP**: the song plays and every pad you hit starts a new slice there. With SNAP on, each cut moves to the nearest hit.
5. The pads under the chop view play the slices (pad 1 = slice 1).
6. **KEEP** puts the slices on pads in a bank you choose. Or tap a slice and then the pad it should go on.

The chop screen remembers where you were when you come back.

## 8. Recording sounds: SAMPLE RECORD

Press **SAMPLE RECORD**.

- **SOURCE**
  - **MIC**: the iPhone or iPad microphone, or a plugged-in mic or audio interface.
  - **RESAMPLE**: records what ChopPad itself plays: your pads and the sequence.
- **LENGTH**: **FREE** (until you stop) or **SEQ** (exactly the length of the sequence, in time with it).
- **START**: **ON REC** (straight away) or **ON SOUND** (waits until something is loud enough).
- **SAVE TO**: the pad the recording goes on (the first empty one is chosen for you). With MIC, tapping a pad chooses it.

Press the big **REC** button to start and again to stop. With MIC, hitting other pads while recording chops the take as you go. **CHOP IT** opens the recording in the chop screen; **UNDO** throws it away.

**SAMPLE RECALL** (SHIFT + SAMPLE RECORD): ChopPad always keeps the last 30 seconds of what came out of it. If you just played something good without recording, this puts it on the first empty pad.

## 9. The sequencer: SEQ

Press **SEQ**. The screen shows the sequence's notes and where the playhead is (bar.beat.step).

- **Knobs**: **BPM** (tempo), **SWING**, **BARS** (1 to 64).
- **◀ ▶** or **− / +**: change sequence. There are **128 sequences**, named A01 to H16. If you change sequence while playing, it switches at the end of the loop, like an MPC.
- **TAP TEMPO**: tap it in time to set the BPM.

**Recording**

- **SEQ RECORD** while stopped makes it blink: it's waiting. **PLAY** then starts recording, with a count-in if COUNT IN is on (SHIFT + pad 4).
- **SEQ RECORD** while playing starts recording right away. Press it again to stop recording.
- **SEQ RECORD's RECALL** (SHIFT + SEQ RECORD): played a good part while *not* recording? This puts what you played over the last pass into the sequence.
- **NOTE REPEAT**: hold it and hold pads for rolls. Tap it quickly to keep it on. While it's on, the screen shows the rate (1/4 to 1/32). **SHIFT + NOTE REPEAT** switches to triplets.

**The chips along the bottom of the SEQ screen**

- **TC**: time correct, the grid notes snap to while recording (OFF, 1/8, 1/16, 1/32).
- **CLICK**: the metronome: ON, REC (only while recording) or OFF. Also SHIFT + TAP TEMPO.
- **PADS**: SOUNDS or SEQS. On SEQS the pads pick sequences instead of playing sounds; PAD BANK + pads 1–8 then chooses the group of 16 sequences. ERASE and COPY work on sequences here.
- **SONG**: song mode. Make a list of sequences (INSERT, REMOVE), and PLAY runs through it. **→ SEQ** turns the whole song into one long sequence.
- **RESAMPLE → PAD**: records the sequence (or the song) onto the first empty pad.
- **ERASE ALL**: clears the sequence.

**STOP**: the first press stops the sequence and lets sounds ring out; a second press silences everything. **PLAY** starts from the beginning; **SHIFT + PLAY** (CONTINUE) carries on from where you stopped.

## 10. Pad play keys: MUTE, LOOP, 16 LEVELS

- **MUTE**: the pads become mute switches. Tap a pad to mute it, live and in the sequence; muted pads turn red. **SHIFT + MUTE** unmutes everything. Press MUTE again to play normally.
- **LOOP**: the selected pad loops. **SHIFT + LOOP** plays the selected pad backwards (REVERSE).
- **CHOP's SHIFT job, NOTE ON**: the selected pad plays only while you hold it. Otherwise it plays to the end (ONE SHOT).
- **16 LEVELS**: puts the selected pad's sound on all 16 pads. **SHIFT + 16 LEVELS** changes the TYPE:
  - **TUNING**: 16 pitches, a semitone apart. OCT − / OCT + on the screen move the range up or down.
  - **VELOCITY**: pad 1 quietest, pad 16 loudest.
  - **FILTER**: pad 1 darkest, pad 16 brightest.

  Press 16 LEVELS again to get your pads back.

## 11. Effects: PAD FX and KNOB FX

### PAD FX
Press **PAD FX**. The pads become 16 effects over the whole beat. An effect is on while you hold its pad, up to 4 at once:

| | | | |
| --- | --- | --- | --- |
| 13 GATE 1/8 | 14 GATE 1/16 | 15 REVERSE | 16 TAPE STOP |
| 9 STUTTER 1/4 | 10 STUTTER 1/8 | 11 STUTTER 1/16 | 12 STUTTER 1/32 |
| 5 VINTAGE | 6 DISTORT | 7 VINYL | 8 ECHO |
| 1 LOW PASS | 2 HIGH PASS | 3 PHONE | 4 BIT CRUSH |

**K1 (DEPTH)** sets how strong they are. **LATCH** on the screen keeps effects on after you let go; **ALL OFF** turns them off.

### KNOB FX
Press **KNOB FX**. One effect for the kit, with two settings on K1 and K2 and the **MIX** on K3:

| Effect | K1 | K2 |
| --- | --- | --- |
| VINTAGE (old sampler grit) | BITS | RATE |
| VINYL (dusty record) | TONE | CRACKLE |
| TAPE (warmth and wobble) | DRIVE | WOW |
| DELAY (in time with the tempo) | TIME | FEEDBACK |
| FILTER (low-pass) | CUTOFF | RESO |
| PUMP (ducks on every beat) | DEPTH | SHAPE |
| COMP (compressor) | AMOUNT | PUNCH |

◀ ▶ on the screen or **SHIFT + KNOB FX** (FX SELECT) changes the effect. It runs on every pad, until you **tap pads on the KNOB FX page**: then only the pads you tapped (lit) go through it. Tap a lit pad to take it out again.

## 12. Kits (projects)

A kit is everything: all 8 banks of pads with their settings, the 128 sequences, the song and the KNOB FX. Your own recordings and samples are saved with it.

Open your kits with **SHIFT + SAMPLE SELECT** (SAVE), **SHIFT + pad 16** (PROJECT), or by tapping the kit's name on the screen. There you can save under a name, load a kit, or start from a factory kit: **Default**, **Soul Session**, **Jazz Club**, **Keys & Strings** and **Organ Trio**. The last row, **About ChopPad**, shows the version.

**UNDO and REDO** (SHIFT + − and SHIFT + +) take back and redo the last changes: recordings, erases, copies, loaded sounds, edits.

## 13. Every key at a glance

| Key | Press | With SHIFT |
| --- | --- | --- |
| SAMPLE | SAMPLE screen; hold + pad selects without playing | INPUT CONFIG (opens SAMPLE RECORD) |
| SEQ | SEQ screen | STEP EDIT (not available) |
| PAD FX | PAD FX screen | FLEX BEAT (not available) |
| KNOB FX | KNOB FX screen | FX SELECT: next effect |
| CHOP | Chop the selected pad's sound | NOTE ON / ONE SHOT |
| MUTE | Mute mode | UNMUTE ALL |
| LOOP | Selected pad loops | REVERSE |
| 16 LEVELS | Selected sound on all 16 pads | TYPE: tuning, velocity, filter |
| SHIFT | Second jobs | |
| PAD BANK | Next bank; hold + pads 1–8 = banks A–H | Bank before |
| ERASE | Hold + pads: erase | COPY |
| NOTE REPEAT | Hold with pads for rolls; tap to keep on | TRIPLET |
| − / + | Pad (or sequence) before / after | UNDO / REDO |
| SAMPLE SELECT | Sounds to load | SAVE (kits) |
| TAP TEMPO | Tap the tempo | METRO: click on, rec only, off |
| SAMPLE RECORD | Record from mic or resample | RECALL: last 30 s onto a pad |
| SEQ RECORD | Record into the sequence (arms when stopped) | RECALL: last pass into the sequence |
| STOP | Stop; again = silence everything | Silence everything |
| PLAY | Play from the start | CONTINUE |

## 14. What's different from the MPC Sample

- **No pressure on the pads.** Phone screens can't feel how hard you hit, so pads always play at full level. Use 16 LEVELS VELOCITY for soft and loud hits, and K1 (DEPTH) for how strong PAD FX are.
- **No fader or data wheel.** Use the knobs, − / +, and tap any number to type it.
- **Not on ChopPad (yet):** STEP EDIT, FLEX BEAT, MIDI, recording knob moves into the sequence, pad link, and mono/poly per pad.
- **Extras the MPC doesn't have:** sampling songs straight from your music library, TAP CHOP, the built-in instruments and ChopPad Records.

---

ChopPad is inspired by Akai MPC samplers and is not affiliated with Akai Professional.
