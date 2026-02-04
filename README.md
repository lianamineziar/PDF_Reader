# 📘 PDF Voice Reader Pro

PDF Voice Reader Pro is a desktop application built using Python and Tkinter that allows users to open PDF files, extract text, and listen to the content using text-to-speech (TTS) technology.  
The application works completely offline and provides a modern GUI with playback controls, voice selection, speed and volume adjustment.

---

## ✨ Features

- 📂 Open and read any PDF file
- 🔊 Offline Text-to-Speech using `pyttsx3`
- ▶ Play, ⏸ Pause, ⏹ Stop audio playback
- ⏪ Skip backward and ⏩ skip forward while reading
- 🎙 Select from available system voices
- ⚡ Adjustable reading speed
- 🔉 Volume control
- 📊 Playback progress bar
- 🧹 Clear loaded text instantly
- 🖥 Clean and modern Tkinter user interface

---

## 🛠 Tech Stack

- **Python 3**
- **Tkinter** – GUI development
- **pyttsx3** – Text-to-Speech engine
- **PyMuPDF (fitz)** – PDF text extraction
- **Pillow (PIL)** – Image handling
- **Threading** – Smooth audio playback

---

## 📁 Project Structure
pdf-voice-reader/
│
├── main.py # Main application file
├── icon.ico # Application icon (optional)
├── README.md # Project documentation
└── requirements.txt # Project dependencies


---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/pdf-voice-reader.git
cd pdf-voice-reader
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pyttsx3 pymupdf pillow
```

### ▶️ Run the Application

```bash
python main.py
```
