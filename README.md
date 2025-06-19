# Smart-Voice-Assistant


## Project Overview
This project is a simple **Voice Assistant** built using Python. It listens to voice commands from the user, processes them, and performs tasks like searching Wikipedia, opening websites, telling the time, and more. It provides a basic demonstration of speech recognition, text-to-speech, and task automation.



##  Features
- Listen to voice commands using the microphone.
- Responds using text-to-speech.
- Search Wikipedia.
- Open web browsers (Google, YouTube).
- Report the current time.
- Launch system applications (like VS Code or browser).
- Conversational basic command handling.


## Libraries Used
- speech_recognition
- pyttsx3
- datetime
- wikipedia
- webbrowser
- os



## How to Run
1. Install dependencies (if not already):
   ```bash
   pip install pyttsx3 SpeechRecognition wikipedia
   ```

2. Run the notebook or convert it to `.py` and run:
   ```bash
   python voice_assistant.py
   ```

3. Make sure your microphone is enabled and working.


## Example Commands
- "Tell me about Python"
- "Open YouTube"
- "What time is it?"
- "Open Google"
- "Launch Visual Studio Code"

## Notes
- Ensure the microphone has access permissions.
- The assistant listens continuously in the notebook; adapt for a GUI or CLI if needed.
- Tested on Windows.


## License
This project is open-source and available under the MIT License.
