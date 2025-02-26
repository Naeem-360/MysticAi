# MysticAI - A Voice Assistant

MysticAI is a voice assistant that can perform various tasks such as opening applications, playing music, retrieving information, controlling volume, and more. It supports both text and voice modes.

## Features
- Voice and text-based interaction
- Open common applications (Chrome, Notepad, File Explorer, etc.)
- Search Google and Wikipedia
- Play YouTube videos
- Take screenshots
- Control system volume
- Provide time and date information
- Open social media sites like Facebook, LinkedIn, and GitHub
- GPT-based chatbot functionality

## Requirements
Ensure you have the following installed before running MysticAI:
- Python 3.7+
- pip (Python package manager)
- The required dependencies (listed below)

## Installation

### 1. Clone the repository
```sh
git clone https://github.com/Naeem-360/mysticai.git
cd mysticai
```

### 2. Install dependencies
Run the following command to install the required libraries:
```sh
pip install -r requirements.txt
pip install pyttsx3 speechrecognition pywhatkit wikipedia requests beautifulsoup4 noisereduce pyautogui pytz geopy fuzzywuzzy openai dotenv PyQt5
```

### 3. Set up the API key
Create a `.env` file in the project directory and add:
```sh
GITHUB_TOKEN=your_openai_api_key_here
```
Replace `your_openai_api_key_here` with your actual API key.

### 4. Running MysticAI
Run the following command:
```sh
python ai_1.py
```
This will launch the GUI for MysticAI.

## Usage
- Type or speak a command (e.g., "open Chrome", "play a song", "what's the time").
- Use "switch to voice" or "switch to text" to change modes.
- Say "help" to see the list of available commands.

## Troubleshooting
- If you encounter missing dependencies, run `pip install -r requirements.txt` again.
- Ensure your microphone is working for voice commands.
- Check if your API key is correctly set in `.env`.

## Contributing
Feel free to fork the repository, make improvements, and submit pull requests! 😄

## License
This project is open-source under the MIT License.



  
 
