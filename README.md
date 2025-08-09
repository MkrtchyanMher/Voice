
# Voice Pitch Detection (TensorFlow / Keras)

This project uses **TensorFlow** and **Keras** to process voice recordings and determine a numerical value representing the **pitch** (fundamental frequency) of the voice.

## Overview

* Takes a recorded voice file (e.g., WAV format)
* Processes and analyzes the audio signal
* Outputs the **pitch** value of the voice in **Hertz (Hz)**

## Purpose

This tool can be used for:

* Speech analysis
* Voice recognition research
* Music and singing studies
* General audio signal processing experiments

## Requirements

* Python 3.8+
* TensorFlow
* Keras (bundled with TensorFlow)
* NumPy, librosa, soundfile (for audio processing)

## Usage

1. Record a voice sample or use an existing `.wav` file
2. Run the program to process the audio
3. View the output pitch value in Hz

## Project Structure

```
Voice/
│
├── data/              # Sample voice files
├── models/            # Trained models
├── scripts/           # Processing and analysis scripts
└── README.md          # Project description
```

## License

This project is open-source and free to use under the MIT License.
