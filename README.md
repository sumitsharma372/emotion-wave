# Speech Emotion Recognition

This project implements a Speech Emotion Recognition (SER) system using deep learning to classify emotions from speech audio files. The workflow is organized into three Jupyter notebooks, each covering a key stage of the process:

## Notebooks

- **1_preprocess_for_one_audiofile.ipynb**: Demonstrates preprocessing and feature extraction for a single audio file, including normalization, noise reduction, and extraction of RMS, ZCR, and MFCC features.
- **2_model.ipynb**: Processes the full dataset, applies feature extraction to all files, prepares labels, splits data, trains an LSTM-based neural network, and evaluates model performance.
- **3_realtime_ser.ipynb**: Enables real-time emotion recognition by recording live audio, preprocessing, extracting features, and predicting emotions using the trained model.

## Features

- Audio normalization and noise reduction
- Feature extraction: RMS, ZCR, MFCC
- Data labeling and one-hot encoding
- LSTM-based emotion classification
- Model training, validation, and evaluation
- Real-time emotion prediction and visualization

## Technologies Used

- Python (Jupyter Notebooks)
- Libraries: librosa, pydub, noisereduce, keras, tensorflow, numpy, matplotlib
- Datasets: RAVDESS, TESS

## Results

- Validation accuracy: ~87%
- Test accuracy: ~84%
- Confusion matrices and per-emotion accuracy
- Real-time emotion analysis

## Getting Started

1. Install required Python packages (see notebook cells for details).
2. Run the notebooks in order:
   - 1_preprocess_for_one_audiofile.ipynb
   - 2_model.ipynb
   - 3_realtime_ser.ipynb
3. Use your own audio files or the provided datasets for experimentation.
