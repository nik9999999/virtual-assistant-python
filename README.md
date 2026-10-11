# Virtual Assistant

A voice-controlled personal desktop assistant for Windows, built in Python as the MCA 4th semester project (2024-2025) at World College of Technology and Management, Gurgaon (Haryana), India.

Inspired by assistants such as Cortana and Siri, it listens to spoken commands, recognizes them, and responds by voice while performing everyday tasks.

## Features
- Date and time: tells the day of the week and the current time
- Wikipedia: speaks a short summary of any topic
- Web: opens Google, Gmail, GeeksforGeeks, runs Google searches and shows the weather
- YouTube: searches and plays videos
- Dictionary: meanings, synonyms, antonyms and translation into Hindi
- Fun: programmer jokes
- Music: plays songs from a local folder
- System: shutdown command, and "bye" to exit

## Tech stack
Python 3.9+, pyttsx3, SpeechRecognition, PyAudio, wikipedia, pywhatkit, pyjokes, PyDictionary, plus the standard `webbrowser`, `datetime` and `os` modules.

## Setup
```bash
git clone https://github.com/<your-username>/virtual-assistant.git
cd virtual-assistant
pip install -r requirements.txt
python main.py
```
A working microphone and internet connection are required (speech recognition uses Google's service). The "play from memory" command expects songs in `D:\songs`; edit the path in `main.py` to change it.

## Example commands
"open google", "tell me the time", "which day it is", "tell me about python from wikipedia", "meaning of serendipity", "play despacito", "search on google python tutorials", "tell me jokes", "bye"

## Project report
The full report (analysis, design diagrams, code explanation, testing, outcomes, limitations and future work) is in [`docs/Virtual_Assistant_Project_Report.docx`](docs/Virtual_Assistant_Project_Report.docx).

## Author
**Nikhil Bhardwaj**, MCA 4th Sem (Roll No. 181360069)
Guide: Ms. Monika Saini, Assistant Professor
