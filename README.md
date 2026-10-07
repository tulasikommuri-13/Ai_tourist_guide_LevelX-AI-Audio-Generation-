# 🌍 AI Tourist Guide – LevelX AI Audio Generation

An AI-powered tourist guide that generates informative and engaging descriptions of tourist destinations using **Google Gemini AI** and converts them into natural-sounding audio using **Murf AI Text-to-Speech**.

## 🌐 Live Demo

👉 **[Try the AI Tourist Guide](https://aitouristguidelevelx-ai-audio-gener.vercel.app/)**

## ✨ Features

- 🤖 AI-powered tourist descriptions using Google Gemini
- 📝 Summary and Detailed explanation modes
- 🌍 Support for English, Hindi, Tamil, and Telugu
- 🎙️ Male and Female voice options
- 🔊 Text-to-Speech using Murf AI
- ▶️ Audio playback directly in the browser
- 💻 Interactive and user-friendly interface
- ☁️ Deployed using Vercel

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript
- Python
- Flask
- Flask-CORS
- Google Gemini API
- Murf AI API
- Vercel
- Git
- GitHub

## 🔄 How It Works

1. Enter a tourist destination.
2. Select **Summary** or **Detailed** explanation.
3. Select a language.
4. Select a voice.
5. Google Gemini generates the tourist description.
6. Murf AI converts the description into speech.
7. The generated description and audio are displayed in the browser.

# 🚀 Setup Instructions

## 1. Clone the Repository

```bash
git clone https://github.com/tulasikommuri-13/Ai_tourist_guide_LevelX-AI-Audio-Generation-.git
cd Ai_tourist_guide_LevelX-AI-Audio-Generation-

2. Create a Virtual Environment
python -m venv .venv

Windows
.venv\Scripts\activate

macOS / Linux
source .venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

🔑 API Key Configuration
Create the following file locally:
Backend/.env

Add your API keys:
GEMINI_API_KEY=your_gemini_api_key
MURF_API_KEY=your_murf_api_key

Important: Never upload your .env file or API keys to GitHub.
The .gitignore file prevents .env and .venv from being committed.
▶️ Run the Application
After activating the virtual environment and configuring the API keys:
python app.py

Open:
http://127.0.0.1:5000

## 📂 Project Structure
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

Note: Backend/.env is a local file and is not committed to GitHub.

## ☁️ Deployment
The application is deployed using Vercel with a Flask/Python backend.

Live Application Testing
1. Open the application.
2. Enter a tourist destination.
3. Select Summary or Detailed mode.
4. Select a language.
5. Select a voice.
6. Click Generate Audio Guide.
7. Verify that the description and audio are generated.
8. Play the generated audio.

## 🎯 Use Cases
- 🗺️ Digital tourist guides
- 🏛️ Historical monument information
- 🎧 Self-guided audio tours
- 🌍 Multilingual tourism assistance
- 📚 Educational tourism applications
- 🤖 AI-powered travel information systems

##🔮 Future Enhancements
- 📍 GPS-based location detection
- 🗺️ Interactive maps and navigation
- 📸 Image-based tourist place recognition
- 🎤 Voice-based user interaction
- 💬 Conversational AI tourist assistant
- ⭐ Personalized recommendations
- 📱 Mobile application
- 🌐 Additional language support
