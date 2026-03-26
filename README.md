# Chroma Quest

A snarky faerie demands you show her specific colors. You have 10 seconds and a webcam.

**[Play it](https://ashleywolf.github.io/chromaquest/)**

Each round, the faerie names a color -- starting easy (RED) and ending absurd (HOLOGRAPHIC MAGENTA). Hold a real-world object up to your webcam's targeting reticle. The game analyzes HSL color values in real time and tells you how close you are. Tolerances tighten as rounds progress.

The faerie has opinions about your performance. She is not kind.

## How it works

- Webcam feed analyzed in HSL color space
- Center reticle samples 100px region, needs 80% pixel match
- 10 color rounds with decreasing tolerance
- Procedural audio feedback: tone pitch changes as you get warmer
- Web Audio API ambient soundtrack
- Snarky NPC dialogue that reacts to success and failure
- Single HTML file, no build step
