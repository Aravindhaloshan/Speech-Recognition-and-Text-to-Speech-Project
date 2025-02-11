# Speech-Recognition-and-Text-to-Speech-Project
This project demonstrates a simple implementation of speech recognition and text-to-speech (TTS) using Python. It allows users to speak into their microphone, converts the speech to text, and then speaks the recognized text back to the user.


## Features
Speech Recognition: Converts spoken words into text using Google's Speech Recognition API.
Text-to-Speech: Converts text into spoken words using the pyttsx3 library.
Ambient Noise Adjustment: Adjusts for ambient noise to improve speech recognition accuracy.

## Prerequisites
Before running the project, ensure you have the following installed:
Python 3.x
SpeechRecognition library
pyttsx3 library
PyAudio library

## Installation

Install the required libraries:
pip install SpeechRecognition pyttsx3 PyAudio

Clone the repository:
git clone https://github.com/Aravindhaloshan/speech-recognition-and-text-to-speech-project.git
cd speech-recognition-tts

## Usage
Run the script:
python speech_recognition.py

## Follow the prompts:

The script will prompt you to remain silent for a moment to adjust for ambient noise.
After the adjustment, speak into your microphone.
The script will recognize your speech, print it to the console, and then speak it back to you.


## Acknowledgments
SpeechRecognition library for speech-to-text conversion.
pyttsx3 library for text-to-speech conversion.
PyAudio library for audio input/output.

