# Medbot- Medical AI Chatbot

## Overview
This project is an AI-powered medical chatbot designed to provide reliable and concise medical advice. The chatbot leverages NLP and deep learning to generate accurate responses while ensuring multilingual accessibility.

## Features
- Uses microsoft/phi-3-mini-4k-instruct model for response generation.
- Language detection and translation for multilingual support.
- Ensures medically relevant responses.
- Optimized for GPU acceleration (CUDA support).
- Deployed using Gradio for an interactive web interface.

## Installation

### Prerequisites
- Python 3.8+
- Pip
- Virtual Environment (recommended)

## Setup
1. Clone the repository:
git clone https://github.com/YOUR_GITHUB_USERNAME/medical-ai-chatbot.git
cd medical-ai-chatbot

2. Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3. Install dependencies:
pip install -r requirements.txt

## Usage
1. Run the chatbot:
python app.py

2. Access the chatbot interface at http://localhost:7860
   
3. Repository Structure
- app.py                # Main chatbot script
- requirements.txt      # Dependencies
- README.md            # Documentation
- models/              # Model files (if applicable)
- data/                # Any necessary datasets (if applicable)
- utils/               # Utility scripts

## API Access
The chatbot requires access to the Hugging Face API. Store your API key in an environment variable:
export HUGGINGFACE_API_KEY='your_api_key_here'

## Future Enhancements
- Expand knowledge base with medical databases.
- Improve response generation with retrieval-augmented generation (RAG).
- Enhance deployment with a web-based front-end.

## Contributors
Yumna Noor

## Acknowledgments
- Hugging Face for model support
- Open-source community for contributions

