# Speech-Recognition-System

This repository contains two complementary projects demonstrating different approaches to speech recognition using Python:

1. Voice-Controlled Assistant (API-Based Speech Recognition)
A simple interactive assistant that listens to spoken commands, converts speech to text using Google Speech Recognition API, and performs basic actions such as opening websites or responding with synthesized speech.
Features

a. Listens to voice commands via the system microphone

b. Converts speech to text using Google’s API

c. Executes commands (e.g., open YouTube, Google, Gmail)

d. Provides spoken responses with pyttsx3

e. Handles errors caused by silence, background noise, or poor network

f. Easily extendable for new commands (e.g., open Gmail, play music, tell the timec)

How it Works 
a. Adjusts for ambient noise before listening 

b. Listens for a short phrase from the microphone 

c. Sends the audio to Google for transcription 

d. Matches the recognized text against predefined commands 

e. Executes the corresponding action and provides spoken feedback


2. MFCC-Based Speech Classification Model (Machine Learning Approach)
3. 
A lightweight machine-learning speech recognition model built using MFCC (Mel-Frequency Cepstral Coefficients) features and Logistic Regression. It classifies short audio clips and evaluates how performance changes when background noise is added.

Features

a. Extracts MFCCs from recorded audio clips

b. Trains a Logistic Regression model for speech classification

c. Performs noise-robustness testing by adding random background noise

d. Visualizes how model accuracy drops as noise increases


How it Works

a. Load and preprocess .wav audio samples

b. Extract 13-dimensional MFCC features from each clip

c. Train a Logistic Regression classifier on labeled samples

d. Evaluate accuracy and generate predictions

e. Test model robustness under varying noise levels

f. Plot “Accuracy vs Noise Level” to visualize performance decline

