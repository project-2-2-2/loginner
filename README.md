# Brainrot Filter for YouTube

## Project Overview
This extension integrates AI to analyze and filter content on YouTube.

## Directory Structure
BrainrotFilter/
├── manifest.json            # Metadata for the browser extension
├── content.js               # Script to modify YouTube UI and call AI API
├── server/
│   ├── server.py            # Python Flask server with AI logic
│   ├── requirements.txt     # Dependencies for the Flask server
└── README.md                # Instructions to run the project

---

## Setup Instructions

### 1. Set Up the AI Server
1. Install Python 3.9 or later.
2. Navigate to the `server/` directory:
   ```bash
   cd server
