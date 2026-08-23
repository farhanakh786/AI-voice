# 🎙️ Continuous AI Voice Assistant with WhatsApp & YouTube

A smart **Python Voice Assistant** that continuously listens for your voice commands and performs tasks like opening YouTube, playing songs, controlling video playback, sending WhatsApp messages, searching Wikipedia, telling jokes, and speaking every response using Text-to-Speech.

This project is beginner-friendly and can be added to your **GitHub portfolio**.

---

## ✨ Features

* 🎤 Continuous voice listening (hands-free assistant)
* 🗣️ Text-to-Speech responses for every command
* ⏰ Tell current time, date, and year
* ▶️ Play YouTube videos or songs by voice
* ⏸️ Pause and resume YouTube videos
* 🔊 Increase or decrease system volume
* 💬 Open WhatsApp Desktop or WhatsApp Web
* 📩 Send WhatsApp messages using voice commands
* 📚 Search Wikipedia and read summaries aloud
* 😂 Tell random programming jokes
* 🌐 Search unknown queries on Google automatically
* 🔁 Keeps asking **"What is the next task?"**
* ❌ Exit anytime with **stop**, **exit**, or **bye**

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Speech Recognition:** `speech_recognition`
* **Text-to-Speech:** `pyttsx3`
* **YouTube Automation:** `pywhatkit`
* **Wikipedia API:** `wikipedia`
* **Browser Automation:** `webbrowser`
* **Keyboard Automation:** `keyboard`
* **Jokes API:** `pyjokes`

---

## 📂 Project Structure

```text
Continuous-AI-Voice-Assistant/
│
├── assistant.py          # Main voice assistant program
├── README.md             # Project documentation
└── requirements.txt      # Python dependencies
```

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Continuous-AI-Voice-Assistant.git
cd Continuous-AI-Voice-Assistant
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes keyboard pyaudio
```

> **Note:** If `pyaudio` installation fails on Windows, install it using a compatible wheel or:

```bash
pip install pipwin
pipwin install pyaudio
```

---

## ▶️ Run the Assistant

```bash
python assistant.py
```

The assistant will greet you and start listening continuously.

Example greeting:

> **Good Morning! I am your voice assistant. I am listening continuously. How can I help you today?**

---

## 🎤 Voice Commands

| Command                            | Action                             |
| ---------------------------------- | ---------------------------------- |
| "What is the time?"                | Tells current time                 |
| "What is today's date?"            | Speaks today's date                |
| "What is the year?"                | Speaks current year                |
| "Open YouTube"                     | Opens YouTube                      |
| "Play Believer on YouTube"         | Plays the requested song/video     |
| "Pause video"                      | Pauses YouTube video               |
| "Resume video"                     | Resumes video                      |
| "Volume up"                        | Increases system volume            |
| "Volume down"                      | Decreases system volume            |
| "Open WhatsApp"                    | Opens WhatsApp Desktop/Web         |
| "Send WhatsApp message"            | Sends a WhatsApp message via voice |
| "Who is Elon Musk?"                | Wikipedia search                   |
| "What is Artificial Intelligence?" | Wikipedia search                   |
| "Tell me a joke"                   | Speaks a random joke               |
| "Stop" / "Exit" / "Bye"            | Closes assistant                   |

---

## 💬 WhatsApp Messaging Setup

Before sending WhatsApp messages, update the contact dictionary inside the code.

```python
contacts = {
    "naina": "+91XXXXXXXXXX",
    "pranshu": "+91XXXXXXXXXX",
    "mum": "+91XXXXXXXXXX",
    "dad": "+91XXXXXXXXXX"
}
```

Replace the placeholder phone numbers with valid WhatsApp numbers in international format.

---

## 🔄 How It Works

1. Assistant greets the user.
2. Continuously listens using the microphone.
3. Converts speech into text.
4. Detects the command.
5. Executes the requested task.
6. Speaks the result.
7. Asks **"What is the next task?"**
8. Repeats until the user says **stop**.

---

## 📸 Example Interaction

```text
Assistant: Good evening! I am your voice assistant.

You: What is the time?

Assistant: The time is 08:45 PM.

Assistant: What is the next task?

You: Play Shape of You on YouTube.

Assistant: Playing Shape of You on YouTube.

Assistant: What is the next task?
```

---

## 📋 Requirements

```text
SpeechRecognition
pyttsx3
pywhatkit
wikipedia
pyjokes
keyboard
pyaudio
```

Create a `requirements.txt` file with the above packages.

---

## ⚠️ Notes

* Requires an active internet connection for YouTube, Google Search, Wikipedia, and WhatsApp Web.
* Microphone permission must be enabled.
* WhatsApp Desktop is opened if installed; otherwise WhatsApp Web is used.
* Keyboard shortcuts work when the target media window is active.

---

## 🚀 Future Improvements

* Wake word support ("Hey Assistant").
* Open desktop applications (Chrome, VS Code, Calculator, etc.).
* Weather updates.
* Email sending through voice.
* AI chatbot integration using OpenAI API.
* Face recognition and voice authentication.
* Multilingual support (English + Hindi).

---

## 👨‍💻 Author

**Farhan Akhtar**

B.Tech – DSAI (Data Science & Artificial Intelligence)

GitHub Project: **Continuous AI Voice Assistant**
