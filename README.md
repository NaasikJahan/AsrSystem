# AsrSystem

## Project Overview
This project demonstrates a basic Automatic Speech Recognition (ASR) system using Python, TensorFlow, SpeechRecognition library, and NLTK. The system converts speech audio to text and performs basic natural language processing (NLP) on the recognized text.

## Features
Audio Data Collection and Upload: Users can upload their own audio files directly in the Colab notebook.
Custom Feature Extraction: Extracts MFCCs, Chroma, Spectral Contrast, Tonnetz, Zero Crossing Rate, and RMS features from audio.
Custom Data Augmentation: Applies time-stretching and pitch-shifting to augment the audio data.
Custom Neural Network: A CNN-RNN hybrid model for more accurate speech recognition.
Custom Training Loop: Provides more control over the training process.
Custom Evaluation Metrics: Includes precision, recall, and F1 score.
Custom Visualization Tools: Visualizes extracted features for better understanding.

## Setup Instructions
Open Google Colab: Go to Google Colab.

Install Required Libraries: Run the following command to install the necessary libraries.
!pip install SpeechRecognition librosa tensorflow nltk

Download NLTK Data Packages: Ensure you have the necessary NLTK data packages.
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')

Upload Your Audio File: Use the file upload function in Google Colab to upload your audio file.

## Conclusion
This project demonstrates a comprehensive approach to building an ASR system with customizations in feature extraction, data augmentation, training, evaluation, and visualization. By following the setup and usage instructions, you can experiment with and extend the system further for your specific needs.
