# JARVIS — Advanced AI Virtual Assistant

<img width="2926" height="1672" alt="image" src="https://github.com/user-attachments/assets/7b39c08f-5014-403c-a2a1-bc61a91a0d51" />

JARVIS is a futuristic, high-performance virtual assistant built using Electron and Python. It features a sleek, cinematic HUD-style interface and delivers real-time intelligence, automation, and system control.

---

## 🚀 System Architecture

### 1. Frontend (Electron HUD)
- Visual Design: Premium glassmorphism UI with real-time audio visualizers, system monitoring, and smooth animations.
- Speech System:
  - STT (Speech-to-Text): Vosk (offline), Groq Whisper, Sarvam
  - TTS (Text-to-Speech): Sarvam (Bulbul v3), Groq Orpheus, Web Speech API
- Interaction: Always-on listening with voice activation and sound-triggered wake system.

---

### 2. Backend (Python MCP Server)
- Model Context Protocol (MCP): Python-based server enabling system interaction.
- Capabilities:
  - System control (app launch, volume, screenshots, etc.)
  - Web scraping and real-time data extraction
  - Browser automation
  - Workspace automation modes (Coding, Research, Relax, Web Dev)

---

### 3. Intelligence Layer
- Groq (Llama Models): Fast intent detection and command routing
- Gemini Flash: Primary conversational engine
- OpenRouter: Backup reasoning and advanced logic

---

## 🛠️ Setup & Installation

### Requirements
- macOS (recommended)
- Node.js (v18+)
- Python 3.10+

---

### 1. Install Dependencies
npm install
pip install fastmcp psutil feedparser requests beautifulsoup4

---

### 2. Configure Environment
Create a `.env` file:

GROQ_API_KEY=your_key  
GEMINI_API_KEY=your_key  
OPENROUTER_API_KEY=your_key  
SARVAM_API_KEY=your_key  

---

### 3. Run Application
npm start

---

## 📦 Build & Export
npm run build

Output will be available in the `dist/` folder.

---

## 🔧 Core Features
- Voice-controlled interaction system  
- Sound-triggered activation  
- Automated workspace setup  
- Real-time system monitoring  
- Persistent memory system  

---

## 👨‍💻 Owner
Himank / Krishna Garg  
Instagram: @ev1lofdestruKtion
