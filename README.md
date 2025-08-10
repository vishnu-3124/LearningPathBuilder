Learning Path Builder (MCP + Gemini + Google APIs)
  An AI-powered Learning Path Builder that creates a personalized, structured learning journey based on user goals and skills — integrating YouTube API, Google Drive API, Gemini API, and Model Context Protocol (MCP) for a seamless, automated experience.

🚀 Features
  🤖 AI-powered content generation using Gemini API
  🎯 Personalized learning plans via Model Context Protocol (MCP)
  📺 YouTube API integration to fetch relevant learning videos
  📂 Google Drive API integration to save learning plans as Google Docs
  📌 Automated playlist creation directly on YouTube
  🔄 Edit and regenerate plans dynamically
  📱 Fully responsive interface

🛠️ Tech Stack
  Frontend: HTML, CSS, JavaScript (Streamlit UI)
  Backend: Python
  AI Model: Google Gemini API
  Context Management: Model Context Protocol (MCP)

APIs:
  YouTube Data API
  Google Drive API

Deployment: Streamlit / Streamlit Community Cloud

📂 Project Structure
  ├── app.py                  # Main application entry point
  ├── mcp_handler.py          # MCP logic and context processing
  ├── youtube_service.py      # YouTube API integration
  ├── drive_service.py        # Google Drive API integration
  ├── requirements.txt        # Dependencies
  └── README.md

🔧 How to Run Locally
1. Clone repository
   `bash
   git clone https://github.com/vishnu-3124/LearningPathBuilder.git

2. Install dependencies

  pip install -r requirements.txt
  
3. Set up API keys

  Get a Gemini API Key from Google AI Studio
  Enable YouTube Data API and Google Drive API in Google Cloud Console
  Save keys in a .env file:

4. Run the app
   streamlit run app.py // app.py = the file name of your py

## 🚀 Live Demo
[**Click here to view the live website**](https://learningpathbuilder-ugwsvy42sq9ffae9v27uth.streamlit.app/)
