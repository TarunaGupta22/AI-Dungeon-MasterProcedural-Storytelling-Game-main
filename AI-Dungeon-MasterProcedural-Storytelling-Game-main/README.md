# 🧙‍♂️ AI Dungeon Master – Interactive AI Storytelling Game

**AI Dungeon Master** is a next-generation storytelling game inspired by *Dungeons & Dragons*, where every choice shapes your destiny.  
Using the power of **Google’s Gemini API**, it generates dynamic, AI-driven adventures that evolve based on player decisions — making each story completely unique.

---

## 🌟 Overview

AI Dungeon Master combines **artificial intelligence**, **interactive fiction**, and **modern web technologies** to create a personalized narrative experience.  
Players can design their own character, explore fantasy worlds, and make choices that influence the flow of the story — all in real time.

Every adventure is procedurally generated, meaning the AI responds intelligently to your actions, maintaining context and continuity throughout the story.

---

## ⚔️ Features

- 🤖 **AI-powered storytelling** using Google Gemini API  
- 🧝 **Custom character creation** (name, race, class)  
- 🗺️ **Dynamic storylines** that evolve with every decision  
- 🌌 **Universe-specific adaptations** for famous characters (e.g., Hogwarts, Middle Earth)  
- 💾 **Persistent story state** that remembers your past choices  
- 🎨 **Clean, responsive UI** inspired by fantasy themes  
- 🔄 **Real-time story continuation** without reloading the page  

---

## 🧠 How It Works

1. The player creates a character and starts a new adventure.  
2. The backend constructs a detailed prompt and sends it to the Gemini API.  
3. The AI generates a structured response with story text and available choices.  
4. The game updates dynamically on the frontend, allowing players to continue their journey instantly.  

This combination of AI and procedural design creates an experience that feels like having your own personal Dungeon Master.

---

## 🧩 Project Structure

AI-Dungeon-Master/
├── frontend/ # React-based UI
│ ├── public/ # Static files and assets
│ └── src/ # Components and logic
├── backend/ # Flask backend
│ ├── app.py # Main API server
│ ├── story_engine.py # AI story generation logic
│ ├── character_recognition.py # Famous character adaptation
│ └── requirements.txt # Python dependencies
└── README.md

-Backend setup
cd backend
python -m venv venv
venv\Scripts\activate    # For Windows
source venv/bin/activate # For macOS/Linux
pip install -r requirements.txt

-Create a .env file in the backend folder
GEMINI_API_KEY=your_api_key_here

-Run the Flask server:
python app.py

-Frontend setup
cd frontend
npm install
npm start

#🧰 Tech Stack

Frontend: React, JavaScript (ES6+), CSS3
Backend: Flask, Python, Flask-CORS
AI Integration: Google Gemini API (Gemini 2.0 Flash)
Development Tools: npm, pip, dotenv, JSON for structured responses

#🚀 Future Enhancements

🎭 Advanced character avatars and image generation
🎧 Voice narration and sound effects
💾 Save/load feature for ongoing adventures
⚔️ Dice-rolling combat system
🌍 More universe templates and world expansions

#🪪 License

This project is licensed under the MIT License.
You’re free to use, modify, and distribute it with proper credit.

#💬 Acknowledgements

Google Gemini API for powering dynamic storytelling
Dungeons & Dragons for inspiring imagination and adventure
The open-source community for their amazing tools and frameworks
