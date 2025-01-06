# Noise-Cancellation-System

# Objective
The goal of this assignment is to develop a real-time noise cancellation system that processes audio in two distinct scenarios:

1. Single Speaker Scenario: In this case, the system isolates and enhances the audio of one primary speaker while treating all other voices and background noises as interference to be minimized or eliminated.

2. Multiple Speaker Scenario: In this case, the system preserves multiple speaker voices and simultaneously filters out environmental noise (e.g., white noise, workplace background noise, or vehicle noise).

# Features
1. Real-time Processing: The system processes live audio input from the microphone and outputs clean, noise-reduced audio.
2. Two Modes: The system can operate in a single speaker scenario or multiple speaker scenario.
3. File Output: The processed audio will be saved as a .wav file.
4. Dynamic Noise Reduction: Adjust the noise reduction level during runtime.

# Requirements
The project requires the following Python packages:
1. numpy
2. pyaudio

# Installation
To install the necessary dependencies, you can use the requirements.txt file.

pip install -r requirements.txt

# How to Use
Run the Python script to start the real-time noise cancellation system.

python noise_cancellation_system.py

The system will ask you to choose between two scenarios:

Enter 1 for Single Speaker Scenario.

Enter 2 for Multiple Speaker Scenario.

The system will start processing audio from your microphone in real-time. You can stop the system by pressing Ctrl+C.


The processed (cleaned) audio will be saved to a .wav file in the output_audio/ directory.
