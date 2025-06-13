
# Business AI Meeting Companion 🧠🎙️

This project is an AI-powered meeting assistant that:
- Transcribes speech to text using OpenAI Whisper
- Summarizes and extracts key points using IBM Watson LLM
- Provides a simple web interface with Gradio

---

## 💡 Features

- 🔊 Audio transcription (MP3 input)
- 📄 Summarization and key point extraction
- 🧪 Easy-to-use interface via Gradio
- 🧠 Uses OpenAI Whisper + IBM Watson + LangChain

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `simple_speech2text.py` | Downloads and transcribes an audio file |
| `hello.py`              | Basic Gradio demo app |
| `speech2text_app.py`    | Upload audio file, see transcription |
| `simple_llm.py`         | Text generation with IBM Watson LLM |
| `speech_analyzer.py`    | Full app: transcribe + analyze with LLM |
| `requirements.txt`      | Python libraries you need |

---

## 🚀 How to Run

1. Clone the repo (or download ZIP)
2. In terminal:
```bash
pip install -r requirements.txt
python3 speech_analyzer.py

