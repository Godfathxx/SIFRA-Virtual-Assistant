**SIFRA - Virtual Assistant**

SIFRA is a virtual assistant designed to perform various tasks and commands using voice recognition. This project leverages natural language processing (NLP) and speech recognition technologies to provide an interactive and intuitive assistant experience.

Overview
SIFRA can execute a range of commands, from opening applications to searching Wikipedia and providing random jokes or advice. It uses voice commands to understand and execute user requests, making it a versatile tool for enhancing productivity and providing entertainment.

Features
Open Applications: Open Notepad, Command Prompt, Camera, and Calculator.
Get IP Address: Retrieve the IP address of the current machine.
Search Wikipedia: Perform searches on Wikipedia using voice commands.
YouTube Playback: Play videos on YouTube.
Random Jokes and Advice: Provide random jokes and advice.
Setup
Prerequisites
Ensure you have the following installed:

Python 3.7+
Virtualenv
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Godfathxx/SIFRA-Virtual-Assistant.git
cd SIFRA
Set up a virtual environment:

bash
Copy code
python -m venv env
Activate the virtual environment:

bash
Copy code
. env/Scripts/activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Running SIFRA
To start SIFRA, run the following command in your terminal:

bash
Copy code
python main.py
Ensure the virtual environment is activated before running the command.

Available Commands
SIFRA can perform the following commands using voice:

Open Notepad: Opens the Notepad application.
Open Command Prompt: Opens the Command Prompt.
Open Camera: Opens the camera application.
Open Calculator: Opens the Calculator application.
What is my IP Address: Retrieves and speaks the IP address of the current machine.
Search on Wikipedia: Searches Wikipedia for a given term.
Play on YouTube: Plays a specified video on YouTube.
Tell me a random joke: Provides a random joke.
Tell me a random advice: Provides a random piece of advice.
Usage
Ensure your microphone is set up and working.
Run SIFRA using the command provided.
Speak the desired command clearly.
Contributing
Contributions are welcome! Please feel free to submit issues or pull requests. If you have suggestions for additional features or improvements, let us know.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Speech Recognition Libraries - For voice recognition capabilities.
Wikipedia API - For Wikipedia searches.
YouTube API - For playing videos on YouTube.
