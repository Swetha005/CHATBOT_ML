# CHATBOT_ML

Swetha's Chat Bot is an AI-powered chatbot built using LangChain, Ollama, and Streamlit. It provides intelligent responses to user queries in a simple web-based interface.

Features

Uses LangChain for prompt handling

-> Powered by Ollama with Llama2 as the AI model
-> Built using Streamlit for an interactive UI
-> Simple and easy-to-use chatbot interface

Installation

Prerequisites

Ensure you have the following installed:

-> Python 3.8+
-> Ollama installed (Download here)
-> Required Python dependencies

Steps

1. Clone this repository:
   git clone https://github.com/yourusername/CHATBOT_ML.git
   cd swetha-chatbot

2. Create and activate a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install the dependencies:
   pip install -r requirements.txt

4. Run the application:
   streamlit run app.py

Usage

-> Enter your queries in the input box
-> The chatbot responds using the Llama2 model from Ollama
-> Modify the prompt template to customize AI behavior
