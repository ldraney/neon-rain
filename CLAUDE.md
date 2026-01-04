# Neon Rain - Lofi Track

A programmatic cyberpunk lofi beat built with Tone.js.

## Vibe
Cyberpunk lofi - neon-lit streets at 2AM, rain on windows, city hum. Dark but energetic.

## Quick Start
Open `index.html` in a browser. Click PLAY.

## Reference
Use ~/lofi-development-docs as cookbook for Tone.js patterns and lofi recipes.

## Technical Specs
- **Key**: F minor (dark, moody)
- **Tempo**: 88 BPM (faster, more drive)
- **Length**: ~3:00

## What We're Trying This Time
- [x] Bitcrusher for lo-fi degradation (8-bit)
- [x] Arpeggiated synth line (16th notes)
- [x] Rain ambience (filtered white noise, separate from vinyl)
- [x] Phaser on pads for movement
- [x] Harder-hitting drums (more punch)
- [x] Syncopated bass line
- [x] Wider stereo field (panning)

## Chord Progression
Fm7 → Db maj7 → Ab maj7 → Eb7
(i → VI → III → VII in F minor - darker modal feel)

## Structure
```
| INTRO | BUILD | DROP A | DROP B | BREAK | DROP C | OUTRO |
   8       8       16       16       8       16       8    = 80 bars (~3:00)
```

- **INTRO**: Rain + filtered arp, no drums
- **BUILD**: Drums fade in, bass enters, filter opens
- **DROP A**: Full groove, arp prominent
- **DROP B**: Add lead melody, more intensity
- **BREAK**: Strip to rain + chords, tension
- **DROP C**: Everything back, peak energy
- **OUTRO**: Elements fade, rain remains

## Sound Design Notes
- Arp: Square wave, bitcrushed, 16th notes following chord tones
- Bass: Saw wave with filter envelope, punchy
- Drums: Harder transients than 3AM Thoughts, more attack
- Pads: Saw through phaser + heavy reverb
- Rain: White noise, bandpass filtered ~1-3kHz, stereo spread

## What's Built
Single `index.html` with:
- Complete 3:38 track with 7 sections
- All instruments (kick, snare, hihat, arp, pad, bass, lead)
- Effects chain (bitcrusher, phaser, ping-pong delay, reverb)
- Rain ambience layer
- Cyberpunk-themed UI with neon gradient title

## Ideas to Explore
- [ ] Add vinyl crackle layer alongside rain
- [ ] Try different arp patterns (up/down vs random)
- [ ] Experiment with tempo (try 92-96 for more energy)
- [ ] Add a counter-melody or harmony line
- [ ] Try different chord voicings (add 9ths/11ths)
- [ ] Add automation to bitcrusher bits during sections
- [ ] Create an alternate "chill" version at 78 BPM
