# Speech-Recognition-System

This project is a simple voice-controlled assistant built with Python. It listens to voice commands through the microphone, converts speech into text using Google’s Speech Recognition API, and performs actions like opening websites. 
It can also respond back to the user with spoken feedback using text-to-speech.

Features
1. Listens to voice commands using the system microphone
2. Converts speech into text with Google Speech Recognition
3. Opens websites (e.g., YouTube, Google) based on recognized commands
4. Provides spoken responses using pyttsx3 
5. Handles errors such as background noise, silence, or poor internet connection
6. Easily extendable to add new commands (e.g., open Gmail, play music, tell the time)

How it Works
1. Adjusts for ambient noise before listening
2. Listens for a short phrase from the microphone
3. Sends the audio to Google for transcription
4. Matches the recognized text against predefined commands
5. Executes the corresponding action and provides spoken feedback
