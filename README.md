# ChopPad

An MPC-style sampler for iPhone and iPad (iOS 17 or later). Pick a song from your music library or record a sound with the mic, chop it into slices, drop them on pads, and make beats with a built-in drum kit and a looping sequencer.

<p align="center">
  <img src="docs/landscape.png" width="640" alt="ChopPad in landscape with the sequencer playing">
</p>
<p align="center">
  <img src="docs/sampler.png" width="220" alt="Sampler: chopping a song into slices">
  <img src="docs/browse.png" width="220" alt="Browsing sounds to load onto pads">
</p>

## Install with SideStore

1. Open **SideStore → Sources → +**
2. Paste this source URL:

   ```
   https://raw.githubusercontent.com/hertn/ChopPad-app/main/source.json
   ```

3. Find **ChopPad** in the source and tap **Get**.

New versions show up in SideStore as updates (pull down in **My Apps** to check). The source also works in AltStore.

**Direct download:** [ChopPad.ipa (latest)](https://github.com/hertn/ChopPad-app/releases/latest/download/ChopPad.ipa), or see [all releases](https://github.com/hertn/ChopPad-app/releases).

## Features

- **Sample your own songs**: load MP3s and other songs stored on your iPhone (not Apple Music streaming tracks) or audio from the Files app. Browse your library by songs, albums, artists or playlists and listen before you pick.
- **Record sounds**: SAMPLE → Record captures the mic (or a plugged-in mic or interface), then you trim, chop and put the take on pads like any song.
- **Pitch it**: make a song or recording higher or lower (±24 semitones) without changing its speed, before chopping; the slices keep that pitch on the pads.
- **Chop**: split a region into even slices, auto-detect hits, or place markers by hand, then put all the slices on pads in one go, or tap a slice and then the pad it should go on, right in the sampler. LOOP repeats the part or a slice so you can hear whether it loops cleanly.
- **4 banks × 16 pads**, with a 16-sound drum kit on bank A out of the box.
- **Change pad sounds easily**: BROWSE loads a drum or sample onto the selected pad; TUNE, LEVEL and PAN knobs on the screen; EDIT for trim, reverse, one shot or hold, and mute groups (it shows which pads are in each group). LOOP on the main screen makes a pad loop (tap on / tap off, or while held). A playhead on the main screen shows what part of the sound is playing.
- **Pad effects**: filter (darker / thinner), drive and reverb on any pad. They're knobs on the main screen and work live, so you can turn them while you play.
- **Hold-and-tap functions** like an MPC: hold CLEAR or COPY and tap pads (tap the button once to lock it on).
- **UNDO**: takes back the last change, whether a recording, CLEAR, COPY, a loaded sound, an EDIT or slices put on pads. The button shows what it will undo.
- **Sequencer**: record what you play into a 1, 2 or 4 bar loop with count-in, metronome, timing correct, swing, undo and erase. Set the tempo with the BPM knob or tap it in with TAP. While it plays, hold a pad to mute its recorded part.
- **Note Repeat**: turn on REPEAT in SEQ, then hold a pad for rolls at 1/4 to 1/32, including triplets.
- **16 Levels**: spread one sound across all 16 pads at different pitches.
- **Kits**: save and load whole setups, including their sequences. Recorded and sampled sounds are saved with the kit.
- Works on iPhone and iPad, in portrait and landscape. One app covers both.

## Support

ChopPad is free, with no ads or subscriptions. If you enjoy it, you can [buy me a coffee on Ko-fi](https://ko-fi.com/hertn).

## Credits

Made by [hertn](https://github.com/hertn). ChopPad is built with Claude, Anthropic's AI: hertn designs and tests the app, Claude writes the code. The version number and credits are in the app under KITS → About ChopPad.

Inspired by Akai MPC samplers; not affiliated with Akai Professional.

## License

All rights reserved. This repo hosts the app's downloads; you're welcome to install it for personal use. See [LICENSE](LICENSE).
