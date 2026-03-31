# organ-men 🎹

A GitHub Pages site featuring an **ASCII art organ player** with **generative music** in the style of Florian Hutter – warm, elegant, nostalgic Unterhaltungsorgel.

## Features

- 🎵 **Generative entertainment music** – endless medley with Schlager, Foxtrott, Walzer, Swing and Beguine chord progressions
- 🎨 **ASCII art organist** – retro green terminal (CRT) aesthetic
- 🎼 **Falling notes animation** – musical notes rain from the top and trigger sounds
- 🔊 **Web Audio API synthesis** – warm organ tones built from harmonic drawbars (sine waves), modelled on Heimorgel / Wersi / Vintage Entertainment Organ
- ✨ **Key lighting** – keyboard keys visually highlight when played

## Live Demo

→ **[mb175.github.io/organ-men](https://mb175.github.io/organ-men)**

## How it works

The music engine uses the Web Audio API to synthesise organ tones by layering multiple sine-wave oscillators at harmonic intervals (drawbar organ simulation). A generative scheduler cycles through Florian Hutter–style chord progressions across five dance styles (Schlager, Foxtrott, Walzer, Swing, Beguine), playing bass notes, inner voices, and a singable melody line simultaneously. Musical note symbols fall from the top of the screen in sync with each beat.

Each style has its own BPM, swing amount, drawbar settings, and set of chord progressions featuring tonal harmonies, secondary dominants, and romantically flavoured voice-leading.

Click anywhere to start.
