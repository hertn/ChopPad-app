# ChopPad

<p align="center">
  <a href="https://github.com/hertn/ChopPad-app/releases/latest"><img src="https://img.shields.io/github/v/release/hertn/ChopPad-app?style=flat&amp;labelColor=15181e&amp;color=2ea44f&amp;label=version" alt="Latest version"></a>
  <a href="https://github.com/hertn/ChopPad-app#install-with-sidestore"><img src="https://img.shields.io/badge/iPhone%20%7C%20iPad-iOS%2017%2B-555?style=flat&amp;labelColor=15181e&amp;logo=apple&amp;logoColor=white" alt="iPhone and iPad, iOS 17 or later"></a>
  <a href="https://ko-fi.com/hertn"><img src="https://img.shields.io/badge/support-%E2%9D%A4%20Ko--fi-ff5e5b?style=flat&amp;labelColor=15181e&amp;logo=kofi&amp;logoColor=white" alt="Support on Ko-fi"></a>
</p>

An MPC-style sampler for iPhone and iPad (iOS 17 or later). Pick a song from your music library or record a sound with the mic, chop it into slices, drop them on pads, and make beats with a built-in drum kit and a looping sequencer.

<p align="center">
  <img src="docs/landscape.png" width="640" alt="ChopPad in landscape with the sequencer playing">
</p>
<p align="center">
  <img src="docs/sampler.png" width="220" alt="CHOP: cutting a song into slices">
  <img src="docs/browse.png" width="220" alt="SAMPLE SELECT: picking sounds for the pads">
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

Laid out like the Akai MPC Sample, with the same keys and names. **[Read the manual](MANUAL.md)** for how everything works.

- **8 banks × 16 pads** (A–H), with a drum kit on bank A and five factory kits to start from.
- **Sample your own songs**: songs stored on your iPhone (not Apple Music streams) or from the Files app. Change the pitch without changing the speed, then chop into even slices, at every hit, by hand, or with TAP CHOP while the song plays.
- **Record sounds** from the mic or an audio interface, or resample ChopPad itself. SAMPLE RECALL catches the last 30 seconds you played.
- **Shape each pad** on the SAMPLE screen's pages: TRIM (start, end, loop point), MIX (level, pan, reverb), AMP (attack, decay, release), TUNE (semitones, cents, WARP to the tempo) and FILTER (classic MPC low-pass, low/high/band-pass, cutoff, resonance).
- **Sequencer**: 128 sequences up to 64 bars, count-in, metronome, time correct, swing, note repeat with triplets, song mode, and resample a sequence onto a pad.
- **PAD FX**: 16 effects over the whole beat, played from the pads (filters, bit crush, vinyl, echo, stutters, gates, reverse, tape stop).
- **KNOB FX**: vintage, vinyl, tape, delay, filter, pump or compressor, on every pad or on the pads you choose.
- **16 LEVELS**: one sound across all 16 pads by pitch, velocity or filter.
- **SHIFT jobs** like the hardware: UNDO/REDO, COPY, half/double sequence, quantize, warp, trim and more.
- **Kits**: save and load whole projects; your recordings and samples are saved with them.
- iPhone and iPad, portrait and landscape, in one app.

## Support

ChopPad is free, with no ads or subscriptions. If you enjoy it, you can [buy me a coffee on Ko-fi](https://ko-fi.com/hertn).

## Credits

Made by [hertn](https://github.com/hertn). ChopPad is built with Claude, Anthropic's AI: hertn designs and tests the app, Claude writes the code. The version number and credits are in the app under KITS → About ChopPad.

Inspired by Akai MPC samplers; not affiliated with Akai Professional.

## License

All rights reserved. This repo hosts the app's downloads; you're welcome to install it for personal use. See [LICENSE](LICENSE).
