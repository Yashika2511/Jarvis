# JARVIS - Desktop Assistant

JARVIS (Just A Rather Very Intelligent System) is a Python-based desktop assistant capable of performing various tasks through voice commands. It integrates multiple APIs and libraries to enhance productivity and automate routine tasks.

## Features
- **Personalized Greetings**: Provides time-based greetings.
- **Voice Recognition**: Interprets voice commands to perform actions.
- **Web Searches**: Search Google, Wikipedia, and YouTube directly from voice input.
- **News Updates**: Fetches the latest news from online sources.
- **System Controls**: Control system functionalities like opening applications, checking system information, etc.
- **WhatsApp Messaging**: Send messages through WhatsApp by voice command.
- **YouTube Controls**: Control YouTube playback.
- **Reminders and Calculator**: Set reminders and perform calculations.
- **Weather and Time Information**: Get current weather and time updates.

## Tech Stack
- **Python**
  - `pyttsx3` for text-to-speech conversion.
  - `SpeechRecognition` for processing voice input.
  - `requests` for fetching web data (news, weather).
  - Other libraries: `datetime`, `os`, `smtplib`, `webbrowser`, etc.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/jarvis-desktop-assistant.git
Navigate to the project directory:

```bash
cd jarvis-desktop-assistant
Create a virtual environment (optional but recommended):

```bash
python -m venv venv
Activate the virtual environment:

## On Windows:

```bash
venv\Scripts\activate
On macOS/Linux:

```bash
source venv/bin/activate
Install the required Python libraries:

```bash
pip install -r requirements.txt
Run the assistant:

```bash
python jarvis.py

