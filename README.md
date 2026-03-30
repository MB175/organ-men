# organ-men 🎹

A GitHub Pages site featuring an **ASCII art organ player** with **generative music** in the style of James Last.

## Features

- 🎵 **Generative organ music** – endless loop with chord progressions (C · Am · F · G and more)
- 🎨 **ASCII art organist** – retro green terminal (CRT) aesthetic
- 🎼 **Falling notes animation** – musical notes rain from the top and trigger sounds
- 🔊 **Web Audio API synthesis** – real organ tones built from harmonic drawbars (sine waves)
- ✨ **Key lighting** – keyboard keys visually highlight when played

## Live Demo

→ **[mb175.github.io/organ-men](https://mb175.github.io/organ-men)**

## How it works

The music engine uses the Web Audio API to synthesise organ tones by layering multiple sine-wave oscillators at harmonic intervals (drawbar organ simulation). A generative scheduler cycles through James Last–style major/minor chord progressions at 108 BPM, playing bass notes, inner voices, and a melody line simultaneously. Musical note symbols fall from the top of the screen in sync with each beat.

Click anywhere to start.
