# Voice Virtual Assistant using ElevenLabs
This project is a real-time voice-enabled assistant built with the [**ElevenLabs Conversational AI API**](https://elevenlabs.io/conversational-ai).
It enables natural spoken conversations by combining speech recognition and AI-driven text-to-speech for lifelike interaction.

## Project Description:
The assistant connects to ElevenLabs’ Conversational AI service and streams audio input/output in real time.
Users can speak directly into their microphone, and the assistant responds instantly with human-like generated speech.

This version is customised as a fitness motivator:
- Tracks personal goals (e.g lose 3kg by April, run 5km without stopping, maintain consistent workouts).
- Provides motivational support and workout ideas.
- Offers daily check-in reminders.

Key features:
- Real-time speech recognition via microphone input.
- Natural AI voice responses powered by ElevenLabs.
- Customisable prompts (e.g fitness coach, study buddy, scheduler).
- Personalised interaction flow which includes goal tracking and daily check-ins.
- Built with Python (requests, PyAudio, dotenv).

Tech Stack:
- Python 3.10+
- ElevenLabs Conversational AI API
- PyAudio for microphone/speaker I/O
- dotenv for secure key management

Acknowledgments:
This project was adapted from the Codédex tutorial [**Create a Voice Virtual Assistant with ElevenLabs**](https://www.codedex.io/projects/create-a-voice-virtual-assistant-with-elevenlabs). 
The core API integration and session setup follow their guide, with additional customisation for personalised use cases.

