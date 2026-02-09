# 🎥 AI-Powered Meeting Summarizer

An end-to-end **AI Meeting Summarizer** that takes a meeting video as input, extracts audio, transcribes the speech using **OpenAI Whisper**, generates a concise summary using **Transformer-based NLP models**, and automatically extracts **action items**.  
The project also includes an interactive **Gradio web interface** for easy usage.

---

## 🚀 Features

- 🎞️ **Video to Audio Extraction**
- 🗣️ **Automatic Speech-to-Text Transcription** using Whisper
- 🧠 **AI-based Meeting Summarization** using BART (facebook/bart-large-cnn)
- ✅ **Action Item Extraction** from meeting summary
- 🌐 **Interactive Web UI** built with Gradio
- 🔌 Supports local execution and API-based workflows

---

## 🛠️ Tech Stack

- **Python**
- **MoviePy** – Audio extraction from video
- **Whisper (OpenAI)** – Speech-to-text transcription
- **Transformers (HuggingFace)** – Text summarization
- **Gradio** – Web-based user interface
- **Groq API** (optional / experimental integration)

---

## 📂 Project Workflow

1. **Upload Meeting Video**
2. **Extract Audio from Video**
3. **Transcribe Audio to Text**
4. **Summarize Transcribed Text**
5. **Extract Key Action Items**
6. **Display Results via Web Interface**

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/meeting-summarizer.git
cd meeting-summarizer

