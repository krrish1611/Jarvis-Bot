# 🤖 Jarvis – Voice-Activated AI Assistant


Jarvis is a smart voice assistant built in Python. It responds to your voice, opens websites, plays music, fetches news, and uses OpenAI’s GPT-3.5 to answer any question you throw at it — just say "Jarvis"!

---

## ✨ Features

- 🎙️ Voice recognition via `SpeechRecognition`
- 🗣️ Text-to-speech using `gTTS` and `pyttsx3`
- 🔍 Web search and site launching (Google, YouTube, Instagram)
- 📰 Real-time news headlines via NewsAPI
- 🎵 Music playback using YouTube links
- 🤖 Chat responses powered by OpenAI GPT-3.5

---

## 📁 Project Structure

.
├── main.py # Main voice assistant logic
├── client.py # Simple OpenAI test client
├── musicLibrary.py # YouTube links to songs
├── .gitattributes # Git line ending config
├── README.md # Project documentation
└── .github/
└── workflows/
└── python-lint.yml # GitHub Actions CI workflow


---

## 🚀 Getting Started

### 🔧 Prerequisites

Install Python dependencies:

```bash
pip install openai speechrecognition pyttsx3 gTTS pygame requests flake8
```
## 🔑 Setup API Keys
In main.py and client.py, replace api_key="" with your OpenAI API key.

In main.py, replace newsapi = "" with your NewsAPI key.

---

## ▶️ Run Jarvis

### Speak "Jarvis" to activate it!

---

## 🎧 Sample Voice Commands
### Here are some things you can say:

"Jarvis"

"Open Google"

"Open YouTube"

"Play starboy"

"News"

"What is coding?, Any questions you wanna ask about!"

---

## ⚙️ GitHub Actions
This repo includes a CI workflow (python-lint.yml) that runs flake8 to check Python code style on every push or pull request.

---

## 📌 Notes
🎤 Make sure your microphone works.

🎶 Add or change music links in musicLibrary.py.

💡 Say "Jarvis" to trigger the assistant.

---

## 🛠️ Built With
Python

OpenAI GPT-3.5

SpeechRecognition

gTTS (Google Text-to-Speech)

pygame

NewsAPI

GitHub Actions

---

## 📄 License
This project is licensed under the MIT License.

---

## 👨‍💻 Author
### Krrish Sah
Feel free to ⭐ the repo, open issues, or submit pull requests to contribute!

---
