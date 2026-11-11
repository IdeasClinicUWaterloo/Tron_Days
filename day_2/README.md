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

# Code You'll Use Today

Today's code is in the `code` folder of the Tron Days files you downloaded in the [prerequisites](../prerequisites/README.md#download-the-tron-days-files):

| Folder | Used in |
|---|---|
| [`PCB_CONNECTION_CHECKER`](../code/PCB_CONNECTION_CHECKER/) | Activity 1: Assemble the Synthesizer |
| [`SYNTH_BASE`](../code/SYNTH_BASE/) | Activity 2: Synthesizer Base Code |
| [`SYNTH_SEQUENCER`](../code/SYNTH_SEQUENCER/) | Activity 3: Sequencer Code |

> Haven't downloaded the files yet? Follow [Download the Tron Days Files](../prerequisites/README.md#download-the-tron-days-files) first.

# Table of Contents

1. [Activity 1: Assemble the Synthesizer](01_assemble_synthesizer.ipynb)
2. [Activity 2: Synthesizer Base Code](02_synth_base_code.ipynb)
3. [Activity 3: Sequencer Code](03_sequencer_code.ipynb)
4. [Day 2 Presentation](04_presentation.ipynb)

---
Back: [Day 1](../day_1/README.md) | Next: [Activity 1: Assemble the Synthesizer](01_assemble_synthesizer.ipynb)
