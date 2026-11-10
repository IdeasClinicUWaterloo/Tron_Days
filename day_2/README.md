---
title: 'Tron Days: Day 2'
---

# Day 2: Building and Programming the Synthesizer

On Day 2 you will assemble your synthesizer, then program it to play notes and full songs.

# The Synthesizer

The synthesizer you will be creating has two modes that you can switch between by pressing a button: the **LFO state** and the **ADSR state**.
Each mode is controlled by potentiometers:

- **LFO state** potentiometers
    - Waveform (sine, triangle, saw, and square waves)
    - Frequency/Pitch
    - Cutoff/Intensity
    - LFO cutoff rate
    - Resonance (i.e., the vibrating quality of the sound)
    - Amplitude/Volume
- **ADSR state** potentiometers
    - Attack
    - Decay
    - Sustain
    - Release

The basic design of the synthesizer also includes one button that plays a single note according to the attack, decay, sustain, and release values.
If you haven't watched it already, [this video](https://youtu.be/mKSo2ANMSEE?si=SVDKjxPIVjyonnV4), which was linked in the [prerequisites](../prerequisites/setup.ipynb), is helpful for understanding how ADSR works and sounds.

# Required Materials

The teaching team will provide you with the following parts to construct the synthesizer.
Before you begin, please make sure that you have all of the materials listed below:

| Component Name | Number of Components |
|---|---|
| Seeeduino Nano | 1 |
| PCB | 1 |
| USB-C Cable | 1 |
| Cardboard Speaker Cab Design (from Day 1) | 1 |

# Getting the Code

You will need the following project folders to run your synthesizer:

- [PCB_CONNECTION_CHECKER](../code/PCB_CONNECTION_CHECKER/)
- [SYNTH_BASE](../code/SYNTH_BASE/)
- [SYNTH_SEQUENCER](../code/SYNTH_SEQUENCER/)

To get them, download this repository as a ZIP: on the repository's main page, click **Code > Download ZIP**, then unzip it.
The project folders are inside the `code` folder.
Keep each `.ino` file inside its folder, since the Arduino IDE needs the folder name to match the sketch name.

# Table of Contents

1. [Activity 1: Assemble the Synthesizer](01_assemble_synthesizer.ipynb)
2. [Activity 2: Synthesizer Base Code](02_synth_base_code.ipynb)
3. [Activity 3: Sequencer Code](03_sequencer_code.ipynb)
4. [Day 2 Presentation](04_presentation.ipynb)

---
Back: [Day 1](../day_1/README.md) | Next: [Activity 1: Assemble the Synthesizer](01_assemble_synthesizer.ipynb)
