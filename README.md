# mit-firefly2-multisamples

24 multisampled synthesizer instruments, rendered from the **MIT-licensed factory patches of Firefly Synth 2 (v2.1.6)**, as FLAC files with ready-to-use SFZ mappings.

Each folder under a category contains one instrument: a `.sfz` file and five 24-bit/48 kHz stereo FLAC samples (one every octave: MIDI keys 36, 48, 60, 72, 84; 4 s held + 1.5 s release tail, velocity 100). The SFZ files map each sample over its key range (`pitch_keycenter`), compensate the level to a common loudness with `volume=` and use `loop_mode=no_loop` (sustain looping is left to the player).

## License

Firefly Synth 2, including its factory presets, is released under the **MIT License** by Sjoerd van Kreel since v2.1.6 (repository: https://github.com/sjoerdvankreel/firefly-synth-2, license file reproduced in `LICENSE`). These renders are audio produced by running that software with those presets; they are provided under the same MIT terms, keeping the original copyright notice and permission notice (`LICENSE`).

## What is not included

Percussion, kick, hat and init (basic waveform) presets are not rendered because they are not meant to be played as pitched multisamples. Patches that clipped or had a silent sample at the highest key were left out (Bass05).

## Categories

- Basses: 6
- Pads: 4
- Strings: 4
- Synths: 10
