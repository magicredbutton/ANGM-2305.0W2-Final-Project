# AudiArt: Music Visualizer

## Repository
https://github.com/magicredbutton/ANGM-2305.0W2-Final-Project

## Description
AudiArt is a program that adapts your song or audio track into a fully synchronized, visual artwork for you to view or download. It's an accessible must-have for artists looking to visually spruce up their creations!

## Features
- Audio Analysis
	- Load an audio file, analyze it before playback using librosa to find all the different frequencies (bass/mid/high) and map them to timestamps. Save data per frame to sync w/ playback.
- Playback Window
	- Play audio w/ pygame, drawing the visuals using the prior analyzed data saved to each frame.
- Visuals: Soft/Sharp
	- Rounder, softer shapes (i.e. circles and varying curves) during quiet sections that pulse with the beat a la Geometry Dash. Transitions to sharper, harder shapes (i.e. spikes and rough polygons) during heavier sections, and vice versa.
- Visuals: Effects/Colors
  - Dynamic effects such as RGB splitting, screen shake, and horizontal slice displacement. Varied color palettes (either preset or customizable) selectable per song or shuffled by key.
- Visuals: Neon Sharp (if time allows)
  - Secondary mode dedicated entirely to sharp visuals and hard-hitting geometry. Toggleable via keybind, bass controls scale, mids control graphic rotation and highs create flickering (epilepsy-safe) visuals.
- Video Export
  - Render each frame with prior analysis, save all frames, combine with original audio using ffmpeg to make an exportable MP4 file.

## Challenges
- Understanding how to use librosa for beat detection and separating frequencies.
- Making sure audio and visuals sync up correctly in pygame.
- Ensuring the more complicated visual effects run fast enough per frame.
- Creating actually cool and fun visuals that don't look terrible or AI generated.
- Combining everything correctly with ffmpeg.

## Outcomes
Ideal Outcome:
- A fully completed visualizer with toggleable Soft/Sharp and Neon Sharp modes, customizable color palettes and interesting beat-driven visual effects. Creates MP4 file of visuals paired w/ audio.

Minimal Viable Outcome:
- A pygame program that plays one audio file and displays visuals in Soft/Sharp mode synced with its bass, beats and volume.

## Milestones

- Week 1 (11/8-11/14)
  1. Push out repo and proposal
  2. Get librosa analysis working and pygame playing synced audio

- Week 2 (11/15-11/21)
  1. Create the soft visuals of Soft/Sharp
  2. Finish the transition to Sharp visuals

- Week 3 (11/22-11/28)
  1. Finish glitch effects synced to beats
  2. Design color palette preset

- Week 4 (11/29-12/5)
  1. Add video export using ffmpeg
  2. Design Neon Sharp visuals if possible
  3. Finishing touches + README
