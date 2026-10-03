# MacroSnap 🍲

MacroSnap is an AI-powered nutrition assistant that analyzes meal images or text descriptions and provides estimated calories and macronutrient information.

## Features

- Upload a photo of your meal
- Describe your meal using text
- Get estimated calories and macronutrients
- Ask nutrition-related questions
- Receive nutrition summaries through WhatsApp

## Tech Stack

- Python
- Streamlit
- Google Gemini API
- Twilio WhatsApp API

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/SarishtiMehta51/Macrosnap.git
cd Macrosnap

2. Install dependencies:

pip install -r requirements.txt

3. Configure the required API keys using Streamlit Secrets:

GEMINI_API_KEY
TWILIO_ACCOUNT_SID
TWILIO_AUTH_TOKEN
TWILIO_WHATSAPP_FROM
TWILIO_CONTENT_SID

4. Run the application:

streamlit run app.py

## How It Works

Users can upload a meal image or describe their meal using text. MacroSnap uses Google Gemini to analyze the meal and provide estimated nutritional information. Users can also receive their nutrition summary through WhatsApp.
