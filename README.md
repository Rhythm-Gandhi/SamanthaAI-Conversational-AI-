# Samantha AI Assistant

A voice-enabled AI assistant with a web frontend, capable of scheduling, email management, recipe guidance, and emotional support.

## Setup

### Backend
1. Navigate to the `backend/` directory.
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Linux/Mac)
4. Install dependencies: `pip install -r requirements.txt`
5. Set up environment variables in `.env` (see `.env.example`).
6. Place `credentials.json` in the `backend/` directory (download from Google Cloud Console).
7. Run the backend: `python sam11.py`

### Frontend
1. Navigate to the `frontend/` directory.
2. Install dependencies: `npm install`
3. Set up environment variables in `.env` (e.g., `REACT_APP_API_URL=http://localhost:5000`).
4. Start the frontend: `npm start`

## Usage
- Open the frontend in your browser (default: `http://localhost:3000`).
- Use voice or text input to interact with Samantha.
- Example commands: "Schedule a meeting", "Tell me a joke", "What’s the time?"

## Deployment
- Push to GitHub: Ensure `.gitignore` excludes sensitive files.
- Deploy the frontend (e.g., via Netlify) and backend (e.g., via Heroku) separately.