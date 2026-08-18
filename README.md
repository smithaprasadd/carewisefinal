# Care-Wise: A Medical Symptom-based Chatbot with WhatsApp Integration

Care-Wise is an AI-powered multilingual health assistant that helps users describe symptoms and receive instant medical guidance, including over-the-counter (OTC) suggestions and natural remedies. It integrates with WhatsApp, supports voice input, and provides smart, concise responses tailored to users' language preferences.

---

## Features

-  **Symptom-based AI Chatbot** using Gemini Pro (Gemini 2.0 Flash)
-  **Multilingual Support** – English, Hindi (हिन्दी), Telugu (తెలుగు)
-  **Voice Input** using Speech Recognition
-  **WhatsApp Integration** via Twilio API
-  **Health Context Awareness** – responds only to health-related inputs
-  **Natural Remedy Suggestions** (when applicable)
-  **Safe Instructions** – No direct diagnoses, only general advice

---

##  Tech Stack

- **Frontend/UI**: Streamlit
- **Backend Intelligence**: Google Generative AI (Gemini 2.0 Flash)
- **Translation**: Google Translate API
- **Speech Recognition**: `speech_recognition` + Google Speech API
- **Messaging Integration**: Twilio WhatsApp API
- **Deployment**: Localhost or Streamlit Cloud

---

##  Folder Structure

```plaintext
.
├── app.py               # Main Streamlit app with navigation
├── integration.py       # Core chatbot logic + language/voice support
├── pages/
│   ├── home.py          # (Custom home page content)
│   ├── chatbot.py       # (Chat UI rendering)
│   └── services.py      # (Additional service descriptions)
└── README.md
