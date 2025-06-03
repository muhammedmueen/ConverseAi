# Conversational AI with Voice Support 🎙️🧠

A smart, voice-activated personal assistant developed as a **college mini project** by **Mueen and Nagesha**, MCA students at **BMSIT, Bangalore**. The assistant listens for a wake word, accepts voice commands, and responds both in text and speech. It can open/close applications, adjust system volume and brightness, enable Windows voice typing, and respond intelligently using Google's Gemini AI.

## 🔧 Features

- 🎤 Wake word activation (e.g., "Purple")
- 🗣️ Voice-controlled commands and responses
- 💬 Text-to-speech + GUI chat log
- 🧠 Gemini AI (Google Generative AI) integration
- 💡 System control:
  - Open/Close apps (Notepad, Chrome, Calculator, etc.)
  - Adjust volume and brightness
  - Enable Windows voice typing (`Win + H`)
- 🌐 Offline and online capabilities
- 🖥️ Intuitive GUI built with Tkinter

## 📁 Folder Structure
  project-root/
├── main.py
├── README.md
├── Requirements.txt
├── conversation_history.txt
└── ...

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Add your Gemini API key in the script.
3. Run the assistant:
   ```bash
   python main.py
   ```
## 🗂️ Voice Commands Supported

| Command         | Action                          |
|-----------------|---------------------------------|
| Purple          | Wake word to activate assistant |
| Open Notepad    | Open Notepad                    |
| Close Chrome    | Closes Chrome                   |
| Increase Volume | Turns up system Volume          |
| Voice typing    | Triggers Windows voice typing   |
| Stop Speaking   | Stop the assistant's voice      |
| Exit/Quit       | Closes the assistant            |


## 📚 Acknowledgements

[Google Generative AI](https://makersuite.google.com/)

Python Libraries: ``` speechrecognition, pyttsx3, tkinter, pycaw, pyautogui ```

## 👨‍💻 Authors

Muhammed Mueen – [LinkedIn](https://linkedin.com/in/muhammedmueen)

Nagesha – [LinkedIn](https://linkedin.com/in/nageshram2003)

