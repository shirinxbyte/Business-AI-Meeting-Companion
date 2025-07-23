# AI Meeting Companion (Speech to Text App)

This project is a beginner-friendly AI meeting assistant that:
- Converts audio (e.g. meeting recordings) to text using OpenAI’s Whisper
- Allows users to upload audio and see transcriptions instantly in a simple web interface (Gradio)
 
## Features

- 🎤 Speech to text using Whisper
- 🌐 Easy-to-use interface via Gradio
- 🐍 Beginner-friendly Python setup

| File | Description |
|------|-------------|
| `simple_speech2text.py` | Downloads and transcribes an audio file |
| `hello.py`              | Basic Gradio demo app |
| `speech2text_app.py`    | Upload audio file, see transcription |
| `requirements.txt`      | Python libraries you need | 


## Installation

```bash
# Create virtual environment
pip install virtualenv
virtualenv my_env
source my_env/bin/activate

# Install dependencies
pip install -r requirements.txt


