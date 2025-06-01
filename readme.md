# 🤖 Gemini Chatbot

A simple and responsive **AI chatbot** built with pure HTML, CSS, and JavaScript, powered by **Google's Gemini API**. This is a **frontend-only project** that lets users interact with an AI assistant in real-time.

---

## ✨ Features

- 🔥 Uses **Gemini 1.5 Flash** API (Google Generative Language API)
- 🧠 AI responds to user queries in a concise (20-word) format
- 💬 Chat-like interface with user and AI chat bubbles
- 📱 Responsive and sleek UI with gradient headings
- 📡 Completely client-side, no backend required

---

## 🚀 Live Demo

https://pratishthass9.github.io/Chatbot/

---

## 🛠️ Technologies Used

- **HTML5** for structure
- **CSS3** for styling
- **JavaScript** for functionality and API integration
- **Google Gemini API** for generating responses

---

## 📁 Project Structure

gemini-chatbot/
│
├── index.html # Main HTML file
├── style.css # CSS styles
├── script.js # JavaScript logic
├── send.svg # Send button icon
├── ai.png # AI avatar
├── user.png # User avatar
├── loading.gif # Loading animation
└── README.md # Project description


---

## 🔑 API Key Setup

This project uses a hardcoded API key for demonstration purposes. In production, **you should not expose API keys on the frontend**.

To use your own key:
1. Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey).
2. Replace the placeholder in `script.js`:

## javascript
const Api_url = 'https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash-latest:generateContent?key=YOUR_API_KEY';

🧪 How It Works
1. User types a message and clicks send.

2. Message appears in the user bubble.

3. A loading animation shows while the AI responds.

4. AI reply appears after a short delay (in 20 words).

## 🌐 Deployment (GitHub Pages)
1. Push this project to a public GitHub repo.

2. Go to Settings > Pages.

3. Set source to main branch, /root folder.

Your site will be live at:
https://pratishthass9.github.io/Chatbot/

## 📜 License
This project is open source and free to use. You can modify it for learning or building your own AI apps.

## 🤝 Acknowledgments
Google Gemini API

Inspired by AI assistants like ChatGPT, Bard, and Claude

## 👨‍💻 Author
Pratishtha Sharma
GitHub
