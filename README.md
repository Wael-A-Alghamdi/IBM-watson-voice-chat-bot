# IBM Watson Voice Chat Bot

A simple voice-based chatbot using IBM Watson cloud services. The system allows real-time voice-to-text and text-to-voice interaction using Python scripts.

---

##  Introduction | المقدمة

This project includes two main functions:

1. **Speech to Text** – Convert spoken input into text and save it.
2. **Text to Speech** – Convert a text response into an audio file.

في هذا المشروع تم تطوير محادثة صوتية باستخدام IBM Watson:  
- التحدث للروبوت وتحويل الصوت إلى نص.  
- رد الروبوت بتحويل النص إلى صوت.

---

##  Part 1: Speech to Text | من خطاب إلى نص

###  Tools Used  
- Python  
- IBM Watson Speech to Text API  
- Visual Studio Code  



The script records audio from the microphone for the specified number of seconds (default: 10).

After recording, the voice is converted to text using IBM Watson.

The text is saved automatically to a file called `output.txt`.

---

##  Part 2: Text to Speech | من نص إلى صوت

###  Tools Used
- Python  
- IBM Watson Text to Speech API  
- Jupyter Notebook

###  How it works
- The script reads either a hardcoded message (like `"hello world"`) or content from `example.txt`.  
- It uses IBM Watson to convert the text into an `.mp3` audio file.  
- The generated file is saved as `winston.mp3`.

---

##  Project Structure

IBM-watson-voice-chat-bot/

├── Speech to Text/

│   ├── transcribe.py

│   ├── setup.py

│   ├── setup.cfg

│   ├── speech.cfg

│   └── output.txt

├── Text to Speech/

│   ├── Text-to-Speech.ipynb

│   ├── example.txt

│   ├── speech.mp3

│   └── winston.mp3

├── README.md

---

##  Notes

- You need an IBM Cloud account and API credentials.  
- Place your API key and region inside the `speech.cfg` file.  
- `transcribe.py` handles the voice recording and transcription.  
- `Text-to-Speech.ipynb` converts any text into spoken audio.  
- This project is intended for educational and demo use only.
