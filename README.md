🌐 Universal Translator App (100+ Languages)

The Universal Translator App is a multilingual translation web application built using Meta’s M2M100 model.
It supports both text and voice input, and provides translated text along with spoken audio output.

This project is ideal for internship submissions, AI/ML portfolios, and real-world language translation use cases.


🚀 Features

• Translate between 100+ languages
• Voice input using microphone or audio file
• Automatic speech-to-text using OpenAI Whisper
• High-quality text translation using Meta M2M100
• Text-to-speech audio output using Google gTTS
• Clean and attractive Gradio user interface
• Public shareable link using Gradio


🛠 Technologies Used

• Python
• Gradio
• Transformers (Hugging Face)
• Meta M2M100 Translation Model
• OpenAI Whisper (Speech Recognition)
• Google Text-to-Speech (gTTS)
• PyTorch
• Torchaudio


📦 Installation
Step 1: Clone the Repository
git clone https://github.com/your-username/universal-translator-app.git
cd universal-translator-app

Step 2: Install Required Libraries
pip install gtts gradio transformers torchaudio


Make sure Python 3.8 or above is installed.


▶️ How to Run the App
python app.py


After running the command, Gradio will generate:
• A local URL
• A public shareable link

Open the link in your browser to use the app.


🧠 How the App Works

User provides text or voice input

Whisper converts audio to text (if voice is used)

M2M100 translates the text into the selected language

gTTS converts translated text into speech

User receives translated text and audio output


🌍 Supported Languages

English, Hindi, Tamil, Telugu, Malayalam, Kannada, Marathi, Gujarati, Bengali, Punjabi, Sanskrit, Urdu, Arabic, French, German, Spanish, Portuguese, Russian, Chinese, Japanese, Korean, and many more (100+ languages supported).


📁 Project Structure
universal-translator-app/
│
├── app.py
├── README.md
└── requirements.txt


🚀 Future Improvements

• Automatic source language detection
• Video subtitle translation
• Mobile responsive UI
• Deployment on Hugging Face Spaces
• Translation history and downloads


👩‍💻 Author

Karthika
AI / ML Enthusiast
Internship Project – Multilingual Translator App

⭐ Support

If you like this project, please ⭐ star the repository and share it.
