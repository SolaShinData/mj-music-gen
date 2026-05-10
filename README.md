# mj-music-gen

# MJ Music Generation with LSTM

A deep learning project that learns from Michael Jackson MIDI files and generates new music using an LSTM model.

## 📌 Project Overview

This project uses the `pretty_midi` Python package to process MIDI data, trains an LSTM neural network on pitch sequences, and generates new MJ-style music.

## 🗂️ Project Structure

```
mj-music-gen/
├── music_generation.ipynb   # Main notebook
├── output/
│   └── generated.mid        # Generated MIDI output
└── README.md
```

> **Note:** The dataset (`clean_midi.zip`) is stored in Google Drive — not included in this repo due to file size.

## 🚀 How to Run

1. Download the dataset from the course page and place MJ MIDI files in a `data/` folder
2. Install dependencies:
   ```bash
   pip install pretty_midi numpy torch
   ```
3. Open and run `music_generation.ipynb` top to bottom

## 📋 Assignment Steps

- Step 1: Load MIDI files using `pretty_midi`
- Step 2: Build pitch vocabulary (skip tracks < 100 notes)
- Step 3: Train LSTM model
- Step 4: Generate new music using trained model
- Step 5: Export and submit `.mid` file(s)

## 🔗 References

- [pretty_midi documentation](https://craffel.github.io/pretty-midi/)
- [pretty_midi tutorial (Colab)](https://colab.research.google.com/github/craffel/pretty-midi/blob/main/Tutorial.ipynb)
- [pretty_midi GitHub](https://github.com/craffel/pretty-midi)
- Dataset: `clean_midi.zip` (provided via course page)
