# Assignment 2: Character Error Rate (CER) Calculation
#notebook9f8e91bf4f.ipynb is the main file 
## Overview
This project calculates the Character Error Rate (CER) for the NPTEL Pure dataset using the Wav2Vec2-large-xlsr-53-english model. The objective is to assess the model's performance in Automatic Speech Recognition (ASR) on Indian English speech data. The dataset comprises audio recordings and corresponding corrected text transcriptions.

## Dataset
The NPTEL Pure dataset (`nptel-pure-set.tar.gz`) includes:
- **Audio Files**: Located at `/kaggle/input/dataset/nptel-pure/wav`
- **Corrected Text Files**: Located at `/kaggle/input/dataset/nptel-pure/corrected_txt`

## Installation
Ensure dependencies are installed:
```bash
pip install torch torchaudio transformers jiwer
