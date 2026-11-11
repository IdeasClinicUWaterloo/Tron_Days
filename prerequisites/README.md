# Tron Days Prerequisites

To help the event run smoothly for you and our team, please read through these instructions and **complete all tasks before Day 1 of Tron Days**.

If you require any additional assistance, please contact us by email at [engideas@uwaterloo.ca](mailto:engideas@uwaterloo.ca), or drop by the second floor Ideas Clinic office in E5-2112, where our co-op research assistants will be happy to help you.

# Required Software

Follow the **[Software Setup guide](setup.ipynb)** to install and configure everything below.

- Audacity
- AutoCAD (free with your UWaterloo student account)
- Arduino IDE, configured for the Seeeduino Nano and the Arduino UNO R4
- Mozzi library **version 1.1.0**, configured for HIFI mode

# Download the Tron Days Files

All of the code and drivers you will need for both days come in one download.
Get them now so they are ready on your laptop for Day 1.

1. **[Click here to download the Tron Days files](https://github.com/IdeasClinicUWaterloo/Tron_Days/archive/refs/heads/main.zip)** (a `.zip` file).
2. Unzip it:
    - **Windows:** right-click the downloaded file, select **Extract All...**, then **Extract**.
    - **macOS:** double-click the downloaded file.
3. Move the unzipped `Tron_Days-main` folder somewhere easy to find, such as your Desktop or Documents.

> **Important:** always open the code from the **unzipped** folder.
> The Arduino IDE cannot correctly open sketches that are still inside a `.zip` file.

Here is what's inside, and when you'll use it:

| Folder | What it is | When you'll use it |
|---|---|---|
| `code/BASIC_CIRCUIT_CHECK` | Plays test waves through your speaker | Day 1: Design Plate and Speaker Cab |
| `code/PCB_CONNECTION_CHECKER` | Checks every button and potentiometer on the PCB | Day 2: Assemble the Synthesizer |
| `code/SYNTH_BASE` | The starter synthesizer code | Day 2: Synthesizer Base Code |
| `code/SYNTH_SEQUENCER` | Plays melodies from lists of notes | Day 2: Sequencer Code |
| `drivers` | The Seeeduino Nano USB driver, only needed if your computer can't find the board's port | Day 1 and Day 2, if needed |

To open a sketch, open its folder and double-click the `.ino` file inside (for example, `code/SYNTH_BASE/SYNTH_BASE.ino`).
Keep each `.ino` file inside its folder, since the Arduino IDE needs the folder name to match the sketch name.

# What to Bring

Please bring pencils, paper, a protractor (optional), and any other tools you may need for sketching or designing.

---
Next: [Software Setup](setup.ipynb)
