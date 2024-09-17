# Jarvis Voice Assistant

Jarvis is a Python-based desktop voice assistant with a sleek graphical user interface (GUI) built using PyQt5. It leverages speech recognition to interpret voice commands and perform tasks such as playing music, taking screenshots, fetching weather updates, opening applications, and more. Jarvis is a lightweight and customizable assistant that helps automate daily tasks efficiently.

## Features

- **Voice Commands:** Control your system using natural speech inputs.
- **GUI:** Animated PyQt5-based GUI with interactive buttons and GIFs.
- **Multitasking:** Perform various tasks like:
  - Playing music
  - Taking screenshots
  - Fetching weather updates
  - Opening applications
  - Searching the web
  - Sending emails
  - System controls like adjusting volume, brightness, etc.
  
- **Speech Recognition:** Uses Python's `speech_recognition` library for interpreting user commands.
- **PyAutoGUI:** Automates tasks such as taking screenshots and interacting with system functions.

## Project Demo


https://github.com/user-attachments/assets/50d06be1-df1b-4c51-b3fe-6b4652c97ce8



## How It Works

1. **Speech Input:** The user gives a voice command via microphone.
2. **Voice Recognition:** The assistant recognizes the command using the `speech_recognition` library.
3. **Task Execution:** Based on the recognized command, the assistant performs the task, such as playing music, taking a screenshot, or fetching weather data.
4. **GUI Feedback:** The PyQt5-based GUI displays visual feedback, including animated GIFs for task status.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/jarvis-voice-assistant.git
   cd jarvis-voice-assistant
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

## Requirements

- Python 3.x
- PyQt5
- SpeechRecognition
- PyAudio
- PyAutoGUI
- Other libraries listed in `requirements.txt`

## Usage

1. **Start the Assistant:**
   - Run the application to initialize the voice assistant and GUI.
   - Use the voice commands, or the GUI buttons, to perform tasks like playing music or taking screenshots.

2. **Example Commands:**
   - "Play music"
   - "Take a screenshot"
   - "What’s the weather?"
   - "Open Google Chrome"
   - "Set a reminder for 10 AM"

## Tools and Technologies

- **Python:** Core programming language used.
- **PyQt5:** For building the interactive graphical user interface.
- **SpeechRecognition:** For converting spoken language into text.
- **PyAutoGUI:** For automating system functions like taking screenshots.

## Challenges & Solutions

- **Integrating GUI with Voice Commands:** Ensured smooth interaction between the voice recognition system and GUI elements by connecting PyQt5 signals and slots with backend functions.
- **Voice Recognition Accuracy:** Overcame issues with noisy inputs by optimizing microphone sensitivity and error handling for unrecognized commands.

## Future Improvements

- **Integration with IoT:** Expanding Jarvis to control smart devices at home.
- **Advanced NLP:** Incorporating natural language processing for more complex voice commands and contextual understanding.
- **Enhanced Customization:** Allow users to configure tasks and personalize the assistant.

## Contribution

Feel free to open issues or pull requests to contribute to this project!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


