# 🏥 Healthcare AI Project

A smart healthcare platform for:
- Booking doctor appointments
- Securely storing medical records
- AI agents for WhatsApp & voice-based booking (Telugu/English)
- Blockchain/IPFS-based confidential file storage

## 📁 Folder Structure
- `frontend/` - HTML/CSS frontend
- `backend/` - FastAPI backend
- `ai_agents/` - WhatsApp and voice AI agents
- `storage/` - Secure file storage (S3/IPFS)
- `docs/` - Planning and architecture docs

## 🚀 Built With
- FastAPI, HTML/CSS, Ollama, LangChain, Whisper, AWS S3

## 👨‍💻 Getting Started
Clone the repo and run the backend:
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
