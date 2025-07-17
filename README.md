# Desktop Voice Assistant 🤖

A Python‑based voice assistant for **Windows** that can greet you, search Wikipedia, tell jokes, send emails/SMS, take notes, control your system, and much more.

## 🔍 Features

- **Speech Recognition** & **Text‑to‑Speech** via `speech_recognition` and `pyttsx3`
- **Wikipedia** lookup
- **Web Automation**: open YouTube, Google, custom apps
- **Media**: play music, take screenshots, web camera capture
- **Email**: send emails via SMTP
- **SMS**: send SMS using Twilio
- **Jokes**: random jokes with `pyjokes`
- **News**: fetch latest headlines via RSS (`feedparser`)
- **Notes**: write/read quick notes
- **System Control**:  
  - Lock workstation  
  - Empty recycle bin  
  - Shutdown system  
- **Calculations**: WolframAlpha queries
- **Extendable**: add your own commands in the main loop

## ⚙️ Prerequisites

- **OS**: Microsoft Windows (uses Windows‑specific modules: `winshell`, `ctypes.windll`)
- **Python**: 3.7+
- **APIs & Accounts**:
  - (Optional) **Twilio** account and API credentials for SMS
  - (Optional) **WolframAlpha** App ID for advanced queries

## 🛠️ Installation

1. **Clone this repo**  
   ```bash
   git clone https://github.com/THEBHARAT08/desktop-voice-assistant.git
   cd desktop-voice-assistant
   ```

2. **Create & activate a virtual environment**  
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure credentials**  
   - Open `jarvis.py` (and/or `sidjar.py`)  
   - Replace email/password or Twilio SID/auth token
   - Insert your WolframAlpha App ID  

## 🚀 Usage

- **Run the main assistant**  
  ```bash
  python jarvis.py
  ```
- **Run the extended version**  
  ```bash
  python sidjar.py
  ```

## 📁 Project Structure

```
├── jarvis.py         # Core assistant
├── sidjar.py         # Extended features
├── requirements.txt  # Python dependencies
└── README.md         # You are here!
```

## 🤝 Contributing

1. Fork the repository  
2. Create a new branch: `git checkout -b feature/YourFeature`  
3. Commit your changes: `git commit -m 'Add some feature'`  
4. Push to the branch: `git push origin feature/YourFeature`  
5. Open a Pull Request  


---

*Happy coding & voice‑controlling!* 🚀
