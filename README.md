 🎙️ AI Voice Assistant (LiveKit + Google Realtime)

This project is an **AI Voice Assistant Agent** built using [LiveKit](https://livekit.io/) and Google's Realtime LLM API.  
It enables **real-time voice conversations** with AI, powered by **Gemini 2.0 Flash Experimental** and LiveKit's voice/room integration.

---

 🚀 Features
- 🎤 Real-time AI Voice Interaction
- 🤖 Powered by **Google Gemini 2.0 Flash Experimental**
- 🔊 Natural voice output (`Puck` voice)
- 🎛️ Enhanced noise cancellation using `BVC`
- 📝 Customizable AI instructions and responses

---

 📂 Project Structure

├── main.py # Main entrypoint of the AI Agent
├── prompt.py # Contains AGENT_INSTRUCTIONS and AGENT_RESPONSE
├── requirements.txt # Python dependencies
├── .env # Environment variables (API keys, etc.)
└── README.md # Project documentation

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>

bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows


bash
pip install -r requirements.txt


env
GOOGLE_API_KEY=your_google_api_key
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret


▶️ Running the Project

bash
python main.py

This will start the AI Voice Assistant Agent and connect it to your LiveKit room.

click Control + C to exit.
