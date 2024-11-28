# Speech AI Assistant

## Overview
The Speech AI Assistant is a Python-based project that integrates OpenAI's Whisper, ChatGPT, and Text-to-Speech technologies to create an intelligent voice assistant capable of interacting in natural language. This project detects wake words, transcribes speech, generates AI-based responses, and outputs spoken replies.

---

## Features
- **Wake Word Detection:** Responds to a predefined trigger phrase.
- **Speech-to-Text Conversion:** Utilizes Whisper for high-accuracy transcription.
- **Natural Language Processing:** Generates responses via ChatGPT.
- **Text-to-Speech Output:** Converts AI-generated responses into speech using gTTS or other TTS libraries.
- **Multi-threaded Processing:** Ensures smooth operation with concurrent audio processing, transcription, and response generation.

---

## Technologies Used
- **Python Libraries:**
  - `speech_recognition` for capturing audio.
  - `pydub` for playing audio.
  - `queue` and `threading` for efficient multi-threading.
  - `dotenv` for environment variable management.
- **OpenAI Whisper:** For robust speech-to-text transcription.
- **ChatGPT API:** For generating human-like responses.
- **Google Text-to-Speech (gTTS):** For synthesizing speech from text.


## Setup and Installation

### Prerequisites
- Python 3.8+
- OpenAI API key (stored in a `.env` file).

### Installation
1. Clone the repository:
   git clone https://github.com/your-repo/speech-ai-assistant.git
   cd speech-ai-assistant

2. Install dependencies:
   pip install -r requirements.txt

3. Set up your `.env` file:
   OPENAI_API_KEY=your_openai_api_key

4. Run the assistant:
   python main.py

## Usage
1. Define the wake word (default: "hey computer").
2. Speak into the microphone when prompted.
3. The assistant will:
   - Detect your wake word.
   - Transcribe your query.
   - Generate a response using ChatGPT.
   - Speak the response back to you.

Google slide presentation - https://docs.google.com/presentation/d/1qj6XuG3s0I7ezwFQeXi3Y-zpUiloMBkjQLlOvYZe9uI/edit?usp=sharing


