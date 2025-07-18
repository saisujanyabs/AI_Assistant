# **🧠 Jarvis AI Assistant**
This is a Python-based AI Voice Assistant that can listen to your voice, process commands, and respond with helpful actions like searching Wikipedia, playing songs on YouTube, telling jokes, checking the time, and opening popular websites.
## **🔧 Features:**

    🎤 Voice recognition using Google Speech API

    🗣️ Text-to-speech responses with pyttsx3

    🌐 Wikipedia search and summary

    🎶 Play songs on YouTube via pywhatkit

    📅 Tells the current time

    😂 Tells random jokes using pyjokes

    🔗 Opens websites like Google, YouTube, GitHub, StackOverflow, and WhatsApp

    💬 Fun responses to common phrases like "How are you?" or "Who are you?"
    
## **🛠️ Technologies Used**
    Python 3
    
    speech_recognition
    
    pyttsx3
    
    wikipedia
    
    pywhatkit
    
    pyjokes
Note: Others listed in requirements.txt

## **🚀 Getting Started**
Clone the Repository

bash: git clone https://github.com/your-username/your-repo-name.git

  cd your-repo-name
Install Dependencies

It's recommended to use a virtual environment:

bash: pip install -r requirements.txt

Make sure you have a working microphone, and install PyAudio (already included in requirements.txt). If installation fails on Windows, you might need to install PyAudio using a .whl file manually.

Run the Assistant

bash: python Assistant.py

Say commands like:

“Search for Sachin Tendulkar on Wikipedia”

“Play Let It Go”

“What is the time?”

“Tell me a joke”

“Open YouTube”

“Goodbye”

## **🧠 How It Works**
The assistant greets you based on the time of day

It listens for your voice command via the microphone.

It uses Google's speech recognition to convert voice to text.

Based on keywords in your command, it performs an action or gives a reply.

## **📝 Requirements**
All required libraries are listed in the requirements.txt file. Install them using:

bash: pip install -r requirements.txt

## **📂 File Structure**
     bash:
     ├── Assistant.py          # Main assistant script
     
     ├── requirements.txt      # List of Python dependencies
     
     └── README.md             # Project documentation
