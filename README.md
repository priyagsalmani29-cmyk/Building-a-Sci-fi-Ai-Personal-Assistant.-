# Building-a-Sci-fi-Ai-Personal-Assistant.-
A module used to automate and communicate with Humanoid Robots.

This code implements a **voice-activated personal assistant** named JARVIS, designed to perform a variety of common tasks such as opening web pages, retrieving information, and interacting with the user through both speech and text.

## Overview
The JARVIS assistant uses natural language processing and speech recognition to receive commands from a user's microphone, then responds with synthesized speech using the pyttsx3 library. It can perform actions such as searching Wikipedia, opening YouTube, Google, Gmail, retrieving weather information, searching online, answering computational and geographical questions using WolframAlpha, downloading Instagram profile pictures, and announcing the current time.

## Main Features
- **Speech Recognition:** Extracts commands via the user's microphone using `speech_recognition` and Google's speech API.
- **Speech Synthesis:** Responds using spoken text with `pyttsx3`, including personalized greetings based on the time of day.
- **Web Automation:** Opens websites including YouTube, Google, Gmail, and StackOverflow based on voice requests.[1]
- **Information Retrieval:** 
  - Searches Wikipedia and reads article summaries aloud.
  - Fetches current weather data using the OpenWeatherMap API.
  - Answers complex questions with WolframAlpha.
- **Instagram Integration:** Requests a username, downloads the user's profile picture, and notifies the user.
- **Personalized Interaction:** Includes custom responses about “emotions”, “age,” or origins, demonstrating interactive conversation capabilities.
- **System Controls:** Can log the user out and shut down, responding to specific commands (“good bye,” “log off,” etc.).

## Code Structure
- **Library Imports:** Includes OS, system utilities, web browser functions, date and time handling, and external APIs.
- **Initialization:** Sets up the speech engine and configures its properties.
- **Functions:**
  - `speak(text)`: Converts text to speech.
  - `wishMe()`: Greets the user based on the current time.
  - `takeCommand()`: Listens for voice commands and converts them to text.
- **Main Loop:** Continuously listens for commands, performs corresponding actions, and handles shutdown or logoff procedures.

## Customization
The notebook is designed to be **modifiable**, allowing users to add new command handlers or integrate additional features as needed.

***

This code provides a comprehensive template for building a desktop-based personal AI assistant with modular, upgradable functionality and interactive voice features.

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/106920569/a78999e5-aec3-4438-96ef-78f5cfcd1ac5/JARVIScodefile.ipynb)
