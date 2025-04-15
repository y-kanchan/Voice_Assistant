# 🎙️ Voice Assistant(Python)

A Python-based voice assistant with a graphical interface built using PyQt5. This application leverages modern speech recognition and synthesis technologies to create an interactive and intelligent assistant that can understand voice commands, respond with synthesized speech, and perform a variety of useful tasks like browsing the web, fetching information from Wikipedia, and telling jokes.

---

## 📖 Description

The Python Voice Assistant is a desktop-based virtual assistant application that responds to user voice commands. It includes a sleek and user-friendly graphical interface, allowing users to start and stop listening with a simple button click.

Under the hood, it integrates several powerful libraries:
- **PyQt5** for building the graphical user interface.
- **SpeechRecognition** for converting spoken words to text.
- **pyttsx3** for converting text responses into speech.
- **Wikipedia API** to provide instant access to summarized knowledge.
- **pyjokes** for delivering a dose of humor.
- **Webbrowser module** to open requested websites directly.

This project is a great starting point for developers interested in creating AI-powered desktop applications or experimenting with natural language processing in Python.

---

## 🚀 Features

- 🎤 Real-time voice recognition
- 🔊 Speech response with pyttsx3
- 🌐 Web browsing via voice command
- 📚 Fetch and speak summaries from Wikipedia
- 😂 Tell programming jokes using `pyjokes`
- 🖼️ Stylish GUI with start/stop listening buttons
- 🎨 Custom design using PyQt5

---
## 🛠️ Installation

Follow the steps below to install and run the project on your local machine:

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/voiceAssistant.git
cd voiceAssistant
```

### Step 2: Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```
### Step 3: Install Required Packages

Make sure you have pip installed. Then install all dependencies with:
```bash
pip install -r requirements.txt
```
⚠️ Note: pyaudio may cause installation issues. If you encounter problems:

- On Windows:
```bash  
pip install pipwin
pipwin install pyaudio
```
- On Linux:
```bash 
sudo apt-get install portaudio19-dev
pip install pyaudio
```
### Step 4: Run the Application
```bash 
python voice_assistant.py
```
🎙️ Speak clearly into your microphone to interact with the assistant.

---

### 📦 Requirements
- Python 3.6 or above
- PyQt5
- pyttsx3
- SpeechRecognition
- wikipedia
- pyjokes
- pyaudio
- 
All dependencies are listed in requirements.txt.

---

### 📸 Screenshot

![start](https://github.com/user-attachments/assets/a3d788f0-d50d-419e-a4b9-e5ba4274a965)
![listen](https://github.com/user-attachments/assets/5b0dc4ab-e291-481b-ac19-c3ffc6493adb)
![time](https://github.com/user-attachments/assets/cfa53912-f575-4e0f-b407-ec090667abc6)

---

### 📄 License
This project is licensed under the MIT License. See the LICENSE file for more information.

---

### 🙌 Acknowledgments

- Python community for its amazing libraries
- Contributors to open-source packages used here
- Users and developers who continue to improve voice-based technologies

---

  







   

