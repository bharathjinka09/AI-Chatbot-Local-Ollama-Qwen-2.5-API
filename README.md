# Ollama Qwen-2.5 Chatbot

This project is a simple chatbot server built with Python FastAPI.

## Prerequsites

As it is a local model, we have to download Ollama and Qwen2.5 model in local before running this API.

## Features
- Chatbot server implementation
- Easy to run and extend

## Setup

1. Create a virtual environment (optional but recommended):
   ```powershell
   python -m venv venv
   .\venv\Scripts\activate
   ```

2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```

3. Run the server:
   ```powershell
   uvicorn server:app --reload --host 0.0.0.0 --port 8000
   ```

## Requirements
See `requirements.txt` for dependencies.

## License
MIT License


