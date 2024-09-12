Title: Speech Recognition System

This project develops a speech recognition system using deep learning techniques. The system recognizes spoken words and transcribes them into text.

Technologies Used:

- Programming Language: Python
- Libraries: TensorFlow, Keras, NumPy, and SciPy
- Framework: Deep Learning
- Dataset: LibriSpeech (1000 hours of audio)

Approach:

1. Data Preprocessing: Audio files are converted to spectrograms and normalized.
2. Model Development: Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs) are used for feature extraction and speech recognition.
3. Training: The model is trained on the LibriSpeech dataset with a batch size of 32 and 100 epochs.
4. Evaluation: The model is evaluated on a test set with metrics like Word Error Rate (WER) and Character Error Rate (CER).
