# OpenAI Chat App

## Setup

### Backend (Node.js/Express)
1. Go to the `server` folder.
2. Run `npm install` to install dependencies.
3. Copy your OpenAI API key into `.env` as `OPENAI_API_KEY`.
4. Run `npm start` to start the backend server (default port 5000).

### Frontend (React)
1. Go to the `client` folder.
2. Run `npm install` (for serve, or use any static server).
3. Run `npm start` to serve the frontend.
4. Open `http://localhost:3000` (or the port shown) in your browser.

## Usage
- Type a message and press Send. The AI will respond using OpenAI's API.

## Security Note
- Never expose your OpenAI API key in frontend code. The backend handles all OpenAI API requests securely.
