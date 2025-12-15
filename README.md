Mental Health & Wellness AI Chatbot
A context-aware AI chatbot exploring ethical guardrails and responsible AI design in mental health support applications.

Disclaimer
This is a research and educational project. This chatbot is not a substitute for professional mental health care, therapy, or medical advice. If you or someone you know is in crisis, please call the 988 Suicide & Crisis Lifeline or contact your local emergency services.

Overview
This project demonstrates multi-layered safety guardrails for AI chatbots in sensitive domains. The system implements:

Input guardrails for topic classification and risk detection
Output guardrails to ensure responses stay within scope
Sentiment analysis for real-time conversation monitoring
Crisis detection and resource referral systems
Responsible AI practices including disclaimer injection and bias checks
Tech Stack
Python, Google Gemini API, Flask, Google Colab, Jupyter

Setup
You'll need a Google Gemini API key. Get one for free at https://makersuite.google.com/app/apikey

Clone the repository:

bash
git clone https://github.com/YOUR_USERNAME/mental-health-chatbot.git
cd mental-health-chatbot
Open the notebook in Google Colab and enter your API key when prompted. Never commit your API key to the repository.

For local setup, install dependencies and run:

bash
pip install -r requirements.txt
jupyter notebook
How It Works
The system uses a multi-layer architecture:

Input guardrails classify user queries and detect potentially harmful or off-topic requests
Gemini API processes the input with context management
Output guardrails verify responses stay within mental health wellness scope
Sentiment analysis tracks emotional tone throughout the conversation
Crisis detection triggers automatic referral to mental health resources when needed
Features
Input filtering detects and redirects off-topic user queries. Output validation ensures chatbot responses remain appropriate and within scope. Sentiment analysis provides positive/negative scoring of conversation tone. Crisis detection automatically refers users to verified mental health resources including the 988 hotline.

Limitations
This chatbot cannot diagnose, treat, or provide medical advice. It is built for exploring ethical AI design, not production deployment. The system relies on Google Gemini API availability and currently supports English only.

Resources
988 Suicide & Crisis Lifeline
Crisis Text Line: Text "HELLO" to 741741
SAMHSA National Helpline: 1-800-662-4357

License
MIT License

