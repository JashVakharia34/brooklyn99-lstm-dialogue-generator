# Brooklyn 99 Dialogue Generator (LSTM)

This project implements a word-level LSTM language model trained on dialogue from the TV show *Brooklyn Nine-Nine* to generate character-style text for Jake Peralta and Captain Holt.

## Model Overview
- Word-level LSTM
- Trained on ~6,400 dialogue lines
- Temperature-based text generation
- CPU friendly training

## Features
- Next-word prediction using LSTM
- Temperature-controlled randomness
- Character-style dialogue generation
- Content filtering during generation

## How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
2. Train the model
python train.py
3. Generate text
generate_text("jake peralta", 14, temperature=0.85)
generate_text("captain holt", 10, temperature=0.5)
Notes
Dataset is not included due to copyright

This project is for educational purposes

Output quality reflects limitations of LSTM models

Author
Jash Vakharia
Himanshu Thakkar
