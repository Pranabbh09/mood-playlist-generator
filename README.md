# Mood Playlist Generator


## 🚀 Overview
Create custom Spotify playlists based on the user's mood. Users describe how they feel (e.g. “happy and energetic”, “calm focus”), and the app translates that into musical attributes (like valence, energy, danceability) to retrieve matching tracks and assemble a playlist.

## Features
- 🎧 Spotify OAuth authentication  
- 📩 Accept mood descriptions in text (or dropdown)  
- 🤖 Map mood input to musical attributes (e.g., OpenAI / custom logic)  
- 🔎 Search Spotify’s catalog using API  
- ✅ Generate, name, and save playlists to user's account  
- 📊 Optionally show audio‑feature analysis of generated playlist

## Tech Stack
- Frontend: React / Vue / plain HTML + JavaScript (choose)
- Backend: Python (Flask/FastAPI) or Node.js (Express)
- Spotify Web API for authentication and playlist creation
- (Optional) OpenAI or NLP module for mood‑to‑song matching
- Database: SQLite / PostgreSQL for user‑data persistence

