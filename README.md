# BidGPT AI Chatbot

BidGPT is an AI-powered chatbot designed to assist users with bidding and tender information. This repository contains the source code for the chatbot, including the backend server, frontend interface, and data ingestion scripts.

## Features
- AI chatbot for bidding/tender queries
- Data ingestion from tender documents
- Web-based user interface

## Project Structure
- `app.js` - Main JavaScript for frontend logic
- `index.html` - Frontend HTML file
- `style.css` - Stylesheet for the frontend
- `server.py` - Backend server (Flask or similar)
- `ingest.py` - Script for ingesting tender data
- `docs/` - Documentation and data files

## Getting Started

### Prerequisites
- Python 3.8+
- Node.js (if using npm packages for frontend)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/bidgpt-ai-chatbot.git
   cd bidgpt-ai-chatbot
   ```
2. (Optional) Create a virtual environment:
   ```sh
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install Python dependencies:
   ```sh
   pip install -r requirements.txt
   ```

### Running the Application
1. Start the backend server:
   ```sh
   python server.py
   ```
2. Open `index.html` in your browser to use the chatbot interface.

## License
Specify your license here (e.g., MIT, Apache 2.0).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
