# DesktopVoiceAssistant-Buddy
Meet Buddy, the groundbreaking desktop voice assistant prioritizing accessibility. Through voice commands and conversational interaction, it assists diverse users, enabling efficient task completion without screen dependency. With a reactive personality and multitasking capabilities, Buddy redefines digital accessibility for all.

# Buddy - Desktop Voice Assistant

Buddy is a Python-based desktop voice assistant designed to assist users with a variety of tasks, primarily focused on voice commands and conversational interactions. 

## Features

- **Voice Interaction**: Communicate with Buddy using voice commands for various tasks.
- **Task Execution**: Conduct searches, retrieve information from Wikipedia, play music on YouTube, fetch news updates, send emails, perform system operations, and more.
- **Personalized Greetings**: Greets the user based on the time of the day.
- **Multifunctional**: Capable of handling multiple commands in a single session.
- **Accessibility Focus**: Aimed at providing assistance to visually impaired and elderly users.

## Usage

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Buddy.git
   cd Buddy

2. Installing necesaary libraries:
Buddy, the desktop voice assistant, utilizes several Python libraries for its functionality. To ensure proper functionality, these libraries need to be imported into your Python environment.

## Required Libraries

- `ctypes`: For low-level operating system interfaces.
- `Queue` from `queue`: For priority queue implementation.
- `shutil`: For high-level file operations.
- `numpy.take`: Specific function from NumPy for array manipulation.
- `pyautogui`: For GUI automation.
- `pyttsx3`: A text-to-speech conversion library.
- `speech_recognition` as `sr`: For speech recognition capabilities.
- `datetime`: For handling date and time.
- `wikipedia`: For fetching data from Wikipedia.
- `webbrowser`: For basic web browsing functionalities.
- `pywhatkit`: For interacting with the web and other functionalities.
- `os`: For basic operating system functionalities.
- `smtplib`: For sending emails.
- `winshell`: For access to Windows shell operations.
- `pyjokes`: For fetching jokes.
- `wolframalpha`: For accessing the Wolfram|Alpha computational knowledge engine.
- `json`: For handling JSON data.
- `GoogleNews` from `GoogleNews`: For fetching news from Google News.
- `URLopener` from `urllib.request`: For opening URLs.
- `application` from `pywinauto`: For Windows GUI automation.
- `subprocess`: For spawning new processes, accessing system commands.

## Installation
Install these libraries via pip, if you haven't already:
```bash
pip install ctypes
pip install pyautogui
pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia
pip install pywhatkit
pip install smtplib
pip install pyjokes
pip install wolframalpha
pip install GoogleNews
pip install pywinauto

3.Install the necessary dependencies:
pip install -r requirements.txt

4.Set up API Keys:
Obtain API keys for services like Wolfram Alpha, Google News, and any other relevant APIs used in the code. Add these keys in the respective sections of the code.

5.Running assistant:
python buddy.py
note:Ensure microphone access for voice input and follow the assistant's prompts for interaction.

6.Acknowledgments
The project utilizes various Python libraries for voice recognition, text-to-speech conversion, and web interactions. Portions of the code are inspired by open-source projects and online tutorials.
