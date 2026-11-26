# Single User Chatbot

A simple chatbot made for only ONE user.
It remembers the full conversation of that single user and replies accordingly.

## Why Single User?
- No login / No multiple users
- Only one chat history is maintained
- Best for personal assistant / personal chatbot

## Features
- Remembers previous messages of the same user
- Continuous conversation, no need to repeat context
- Uses Google Gemini API for replies
- Uses LangGraph for memory management

## Files in this project
- `memorymgtwithlanggraph.py` - Main chatbot with single-user memory
- `second.py` - Chatbot logic / setup
- `third.py` - Testing / extra logic
- `requirements.txt` - All libraries needed

## How to Run

1. Clone this repo
```bash
git clone https://github.com/Anjalikapoor123/Single-user-chatbot.git

##Installation libraries

pip install -r requirements.txt

##Create .env file and add your key

GOOGLE_API_KEY=your_gemini_api_key_here

##Run chatbot

python memorymgtwithlanggraph.py
