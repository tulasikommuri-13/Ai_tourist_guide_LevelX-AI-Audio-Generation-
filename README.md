# 🌍 AI Tourist Guide – LevelX AI Audio Generation

An AI-powered tourist guide that generates informative and engaging descriptions of tourist destinations using **Google Gemini AI** and converts them into natural-sounding audio using **Murf AI Text-to-Speech**.

## 🌐 Live Demo

👉 **[Try the AI Tourist Guide](https://aitouristguidelevelx-ai-audio-gener.vercel.app/)**

---

## ✨ Features

- 🤖 AI-powered tourist descriptions using Google Gemini
- 📝 Summary and Detailed explanation modes
- 🌍 Support for English, Hindi, Tamil, and Telugu
- 🎙️ Male and Female voice options
- 🔊 Text-to-Speech using Murf AI
- ▶️ Audio playback directly in the browser
- 💻 Interactive and user-friendly interface
- ☁️ Deployed using Vercel

---

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask
- Flask-CORS

### AI & APIs
- Google Gemini API
- Murf AI Text-to-Speech API

### Deployment & Tools
- Vercel
- Git
- GitHub
- VS Code

---

## 🔄 How It Works

1. Enter the name of a tourist destination.
2. Select the explanation type:
   - Summary
   - Detailed
3. Select a language.
4. Select a voice.
5. The frontend sends the request to the Flask backend.
6. Google Gemini generates the tourist description.
7. Murf AI converts the generated description into speech.
8. The generated audio is returned to the frontend.
9. The description and audio are displayed in the browser.

---

# 🚀 Setup Instructions

## 1. Clone the Repository

```bash
git clone https://github.com/tulasikommuri-13/Ai_tourist_guide_LevelX-AI-Audio-Generation-.git
cd Ai_tourist_guide_LevelX-AI-Audio-Generation-
```

## 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### Windows

```bash
.venv\Scripts\activate
```

### macOS / Linux

```bash
source .venv/bin/activate
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 API Key Configuration

The application requires API keys for:

- Google Gemini
- Murf AI

Create the following file locally:

```text
Backend/.env
```

Add your API keys:

```env
GEMINI_API_KEY=your_gemini_api_key
MURF_API_KEY=your_murf_api_key
```

Replace the placeholder values with your actual API keys.

### ⚠️ Important

Never upload your `.env` file or API keys to GitHub.

The `.gitignore` file prevents `.env` and `.venv` from being committed to the repository.

---

# ▶️ Run the Application Locally

After activating the virtual environment and configuring the API keys, run:

```bash
python app.py
```

The Flask server will start locally.

Open the application in your browser:

```text
http://127.0.0.1:5000
```

---

# 📂 Project Structure

```text
AI_tourist_guide_LevelX-AI-Audio-Generation/
│
├── Backend/
│   └── .env
│
├── Frontend/
│   ├── index.html
│   ├── index.js
│   └── package-lock.json
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md
```

> **Note:** `Backend/.env` is a local configuration file and is not committed to GitHub.

---

# 🔐 Environment Variables

| Variable | Description |
|----------|-------------|
| `GEMINI_API_KEY` | API key used to generate tourist descriptions using Google Gemini |
| `MURF_API_KEY` | API key used for text-to-speech generation using Murf AI |

---

# ☁️ Deployment

The application is deployed using **Vercel** with a Flask/Python backend.

## Live Application

👉 **https://aitouristguidelevelx-ai-audio-gener.vercel.app/**

Environment variables are configured securely in Vercel and are not exposed in the source code.

---

# 🧪 Testing

To test the application:

1. Open the application.
2. Enter a tourist destination.
3. Select **Summary** or **Detailed** mode.
4. Select a language.
5. Select a voice.
6. Click **Generate Audio Guide**.
7. Verify that the tourist description is generated.
8. Verify that audio is generated.
9. Play the generated audio in the browser.

---

# 🎯 Use Cases

- 🗺️ Digital tourist guides
- 🏛️ Historical monument information
- 🎧 Self-guided audio tours
- 🌍 Multilingual tourism assistance
- 📚 Educational tourism applications
- 🤖 AI-powered travel information systems

---

# 🔮 Future Enhancements

- 📍 GPS-based location detection
- 🗺️ Interactive maps and navigation
- 📸 Image-based tourist place recognition
- 🎤 Voice-based user interaction
- 💬 Conversational AI tourist assistant
- ⭐ Personalized tourist recommendations
- 📱 Mobile application
- 🌐 Additional language support

---

# 👩‍💻 Project Information

**Project:** AI Tourist Guide – LevelX AI Audio Generation

**Technologies:** Python, Flask, JavaScript, Google Gemini, Murf AI

**Deployment:** Vercel

**GitHub Repository:**  
https://github.com/tulasikommuri-13/Ai_tourist_guide_LevelX-AI-Audio-Generation-

**Live Demo:**  
https://aitouristguidelevelx-ai-audio-gener.vercel.app/

---

## ⭐ Acknowledgement

This project was developed as part of the **LevelX AI Audio Generation** project to demonstrate the integration of Generative AI and Text-to-Speech technologies for an interactive tourism experience.
