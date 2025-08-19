# MCQ GENERATOR APP
An intelligent Multiple Choice Question (MCQ) generator that creates specific, detailed quiz questions using Google Gemini AI. Built with Streamlit for an intuitive web interface.

📦 Installation

Clone the repository:
bash git clone https://github.com/Mithila-Mane/mcq-generator.git
cd mcq-generator

Install dependencies:
bash pip install -r requirements.txt

Get your Google Gemini API Key:

Visit Google AI Studio
Sign up for a free account
Generate an API key


Run the application:
bash streamlit run app.py


🔑 API Key Setup
Two ways to configure your API key:
Option 1: Environment Variable (Recommended)

Create a .env file in the project root:
GOOGLE_API_KEY=your_api_key_here


Option 2: Direct Input

Enter your API key directly in the sidebar when running the app
Key is stored for the current session only
