# Python-Project
This project will demonstrate the integration of voice recognition, Natural Language Processing (NLP), and simple automation using Python.
# 🎙️ Voice-Activated AI Chatbot

## 🧠 Project Overview

The **Voice-Activated AI Chatbot** is a Python-based assistant that listens to voice commands and performs tasks like searching Wikipedia, opening websites, fetching system information, and responding through speech.  
This project demonstrates the integration of **Speech Recognition**, **Text-to-Speech (TTS)**, and **Natural Language Processing (NLP)** for intelligent human–computer interaction.

---

## 🚀 Features

- 🎤 **Voice Command Recognition** — Converts spoken words into text using `speech_recognition`.
- 🗣️ **Text-to-Speech Response** — Uses `pyttsx3` to reply audibly.
- 🌐 **Wikipedia Search** — Retrieves summaries from Wikipedia.
- 🕓 **Time & Date Queries** — Tells the current time.
- 🌍 **Web Automation** — Opens websites like Google, YouTube, etc.
- 💻 **System Commands** — Executes shutdown, restart, and other OS-level commands.
- 📝 **Custom Commands** — Add personalized functions such as note-taking or reminders.
- ⚙️ **Error Handling** — Handles unrecognized speech gracefully.

---

## 🧩 Technologies Used

- **Python 3.8+**
- `speech_recognition`
- `pyttsx3`
- `wikipedia`
- `webbrowser`
- `datetime`, `os`, `time`, `subprocess`, `ctypes`, etc.

---

## 🛠️ Setup Instructions


### 1. Install Dependencies

pip install speechrecognition pyttsx3 wikipedia

## ⚙️ How It Works
- The bot listens for a voice command using your system microphone.
- It processes the speech input and converts it into text.
- Depending on the command, it:
    (1)Opens a website.
    (2)Fetches Wikipedia data.
    (3)Announces the current time.
    (4)Executes a system task.
- The chatbot replies audibly via the pyttsx3 text-to-speech engine.

## 💡 Example Commands
|Command	|Description|
|--------------|---------------|
|“Open Google” |	Launches Google in the default browser|
|“Search Wikipedia for Albert Einstein”	|Fetches a summary from Wikipedia|
|“What is the time?”|Speaks the current time|
|“Shutdown the system”|	Initiates a system shutdown|
|“Write a note”|	Creates a text note file|

## 🔧 Optional Enhancements
- Add a personalized greeting system
- Include to-do list or reminder functionality


## 🧪 Testing
- Test the chatbot using different microphones and accents.
- Adjust pause_threshold in the speech_recognition module for better response timing.
- Validate error handling for unrecognized or empty voice input.


## Conclusion
The project demonstrates how Speech Recognition, Text-to-Speech, and Python automation can create an efficient AI voice assistant. It highlights the potential of natural language interfaces and forms a base for future intelligent personal assistants.


## 🧑‍💻 Author
**[Niththiyapoorani]**
📧 [https://github.com/Niththiyapoorani]
📅 Year: 2025
📘 Project Type: Python / Business Intelligence / Business Analysis / Data Analysis
