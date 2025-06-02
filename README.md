# 🤖 VOX – AI Voice Assistant (Python, Modular)

**Creator:** Ahmad Babagana Lawan  
**Mode:** Terminal-based (GUI version in planning)  
**Version:** VOX v1.0 – *online Mode*

---

## ✨ What is VOX?

VOX is a **voice-controlled AI assistant**, built with love and Python.  
Designed to act, learn, and speak.  

You activate VOX by saying **“Hey VOX”**, then issue commands like:
- “Open calculator”
- “What’s my name?”
- “Remind me to train at 9 PM”
- “Tell me a joke”

All responses are spoken back to you.

---

## 🎯 Core Features

✅ Voice recognition and command handling  
✅ Fun features: jokes, motivation, cool responses  
✅ Tells time, date  
✅ Opens apps, controls system  
✅ Web search 
✅ Local memory: "Remember my name is Ahmad"  
✅ Voice-powered reminders (persistent)  
✅ Modular design: Easy to add your own skills  
✅ Lightweight, fast, and secure

---

## 🧱 Project Structure

VOX/
├── main.py # Entry point
├── core/ # Wake word, voice recognition, memory
├── commands/ # All skill modules (open apps, jokes, etc.)
├── data/ # Stored memory and reminders
├── requirements.txt # Install dependencies
└── README.md # This file


---

## 🛠 Requirements
- Installed system microphone

### Python Packages:
- `speech_recognition`
- `pyttsx3`
- `numpy`
- `pyaudio`

---

⚙️ Commands You Can Say
“Hey VOX” (wake word)

“Open browser” / “Open calculator”

“Tell me a joke”

“What’s the time?”

“Remember my name is Ahmad”

“What’s my name?”

“Remind me to train at 6 PM”

And many more...

🧠 Architecture Philosophy
VOX is built to be:

💡 Modular → All skills in commands/

🧠 Expandable → Add your own voice commands

🔐 Private → No cloud calls

🕶 Minimal → Voice-first with clean terminal UI

🧪 Planned Upgrades (Coming Soon)
 GUI version with mic button, speech log

 ChatGPT or Ollama optional integration

 Support for background listening mode

 In-memory assistant for multiple users

 Lightweight Android port (voice-only)

💬 Creator's Note
“VOX started as a dream — and became my way of learning how far I could go.
It’s proof that even if you're busy, tired, or self-taught — with patience and intention,
you can build anything you imagine.”

— Ahmad Babagana Lawan

🫡 Final Words
If you're reading this... VOX is real. It works.
