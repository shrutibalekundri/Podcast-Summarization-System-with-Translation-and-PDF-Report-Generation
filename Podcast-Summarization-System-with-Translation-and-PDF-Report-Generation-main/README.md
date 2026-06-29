# 🎙️ AI Podcast Summarization System with Translation & PDF Report Generation

<p align="center">
<img src="https://img.shields.io/badge/React.js-Frontend-61DAFB?style=for-the-badge&logo=react">
<img src="https://img.shields.io/badge/Flask-Backend-000000?style=for-the-badge&logo=flask">
<img src="https://img.shields.io/badge/Google-Gemini-blue?style=for-the-badge&logo=google">
<img src="https://img.shields.io/badge/OpenAI-Whisper-412991?style=for-the-badge&logo=openai">
<img src="https://img.shields.io/badge/HuggingFace-NLP-yellow?style=for-the-badge&logo=huggingface">
</p>

---

# 📖 About the Project

The **AI Podcast Summarization System** is an intelligent NLP-powered web application that transforms lengthy podcasts and video content into concise, multilingual summaries. Users can provide a YouTube link or upload a video, and the system automatically extracts audio, generates transcripts, creates AI-powered summaries, translates the content into multiple languages, and exports the results as a professionally formatted PDF report.

---

# ✨ Key Features

* 🎥 YouTube Video & Local Video Processing
* 🎧 Automatic Audio Extraction
* 📝 Speech-to-Text Transcription using OpenAI Whisper
* 🤖 AI-Powered Podcast Summarization
* 🌍 Multi-Language Translation
* 📄 PDF Report Generation
* 💬 AI Chatbot for Podcast Q&A
* 📊 Clean & Responsive Dashboard
* ⚡ Fast Processing Pipeline

---

# 🛠️ Technology Stack

| Category         | Technologies                                                 |
| ---------------- | ------------------------------------------------------------ |
| Frontend         | React.js, HTML5, CSS3, JavaScript                            |
| Backend          | Flask (Python)                                               |
| AI Models        | Google Gemini API, OpenAI Whisper, Hugging Face Transformers |
| Video Processing | yt-dlp, MoviePy                                              |
| Translation      | Google Translate API / Custom Translation                    |
| PDF Generation   | html2pdf.js                                                  |
| Optional AI      | pyannote.audio (Speaker Diarization)                         |
| Version Control  | Git & GitHub                                                 |

---

# 🏗️ System Workflow

```text
YouTube URL / Video Upload
            │
            ▼
     Audio Extraction
            │
            ▼
 Speech-to-Text (Whisper)
            │
            ▼
 AI Text Summarization
            │
      ┌─────────────┐
      ▼             ▼
 Translation    AI Chatbot
      │             │
      └──────┬──────┘
             ▼
      PDF Report Generation
```

---

# 📂 Project Structure

```text
Podcast-Summarization-System/
│
├── frontend/
│
├── nlp_engine/
│   ├── app.py
│   ├── chatbot.py
│   ├── summarizer.py
│   ├── translate.py
│   └── utils.py
│
├── uploads/
├── audios/
├── requirements.txt
├── package.json
├── .gitignore
└── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Podcast-Summarization-System.git
```

## Backend

```bash
cd nlp_engine
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

## Frontend

```bash
cd frontend
npm install
npm start
```

Open:

```
http://localhost:3000
```

---

# 📱 Application Workflow

1. Paste a YouTube video URL or upload a video.
2. Extract audio from the video.
3. Generate speech transcription.
4. Produce an AI-generated summary.
5. Translate the transcript or summary into the selected language.
6. Download a structured PDF report.
7. Ask questions using the AI chatbot for deeper insights.


---

# 🌍 Supported Functionalities

* YouTube Podcast Processing
* Audio Extraction
* Automatic Speech Recognition
* AI Summarization
* Multi-language Translation
* PDF Export
* Conversational AI
* Responsive User Interface

---

# 🔮 Future Enhancements

* Speaker Identification
* Keyword Extraction
* Sentiment Analysis
* Podcast Topic Classification
* Audio Timestamp Navigation
* Voice-to-Voice Translation
* Cloud Storage Integration
* Batch Podcast Processing
* User Authentication & History

---

# 👩‍💻 My Contributions

* Developed the React.js frontend interface.
* Built the Flask backend and REST APIs.
* Integrated OpenAI Whisper for speech recognition.
* Implemented AI-powered summarization using Gemini and Hugging Face.
* Developed multilingual translation functionality.
* Created automated PDF report generation.
* Designed the AI chatbot for podcast-based question answering.

---

# ⭐ Project Highlights

* End-to-End AI Automation
* Multilingual NLP Pipeline
* Full-Stack Web Application
* Modern Responsive UI
* AI Chatbot Integration
* PDF Report Export
* Scalable Modular Architecture

---

# 📄 License

This project is developed for educational and research purposes.

---

<p align="center">

⭐ If you found this project useful, consider giving it a star!

**Transform Hours of Podcasts into Minutes of Insights with AI. 🚀**

</p>
