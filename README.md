# Personalized AI Assistant with Voice Control

This project is a Python-based personalized AI assistant that uses voice commands to perform tasks such as opening applications, controlling system volume, browsing websites, and responding to queries via OpenAI's GPT-3.5 API. The assistant also includes a user-friendly graphical interface built using Tkinter.

## Features

- **Voice Interaction**: Recognizes user voice commands and executes tasks.
- **GUI Interface**: Simple start/stop buttons to control the assistant.
- **Web Automation**: Opens websites (e.g., YouTube, Facebook) and performs searches using Selenium.
- **Application Management**: Launches applications like Word, Excel, and PowerPoint.
- **System Volume Control**: Adjusts, mutes, or unmutes system volume.
- **OpenAI Integration**: Uses GPT-3.5 to process and respond to advanced commands.
- **Memory Feature**: Stores user-specific details for personalization.
- **Multithreading**: Runs tasks in the background without freezing the UI.


## Requirements

### Python Libraries
Install the following Python libraries using pip:
```bash
pip install speechrecognition pyttsx3 openai selenium pycaw psutil comtypes
```

### Additional Requirements
1. **ChromeDriver**:
   - Download ChromeDriver compatible with your Chrome version from [ChromeDriver](https://chromedriver.chromium.org/downloads).
   - Update the path in the code (`E:\AI Jarvis\chromedriver-win64\chromedriver.exe`).
2. **Microsoft Office Applications**:
   - Ensure Word, Excel, and PowerPoint are installed and their shortcuts are accessible via the paths in the code.
3. **Microphone**:
   - A working microphone is required for speech recognition.

---

## Setup Instructions

1. Clone this repository or copy the code to your local system.
2. Update the OpenAI API key:
   - Replace `openai.api_key` with your OpenAI API key.
3. Install the required Python libraries and tools as listed above.
4. Run the script using:
   ```bash
   python assistant.py
   ```
5. Interact with the assistant via voice commands or the GUI.

---

## Voice Commands Examples

- **System Volume Control**:
  - "Mute volume" / "Unmute volume" / "Volume up" / "Volume down"
- **Open Applications**:
  - "Open Word" / "Open Excel" / "Open PowerPoint"
- **Open Websites**:
  - "Open YouTube" / "Search for [topic] on YouTube" / "Open Facebook"
- **Close Applications**:
  - "Close browser" / "Close application"
- **General Commands**:
  - "Tell me a joke" (processed via GPT-3.5)

---

## File Structure

- **`assistant.py`**: Main script containing the assistant's functionality and GUI setup.
- **ChromeDriver**: Ensure the executable is placed in the path specified in the code.

---

## Known Issues

1. **Speech Recognition Errors**:
   - Ensure a stable internet connection for Google Speech Recognition.
2. **Application Path Errors**:
   - Verify that the paths to Word, Excel, and PowerPoint shortcuts are correct.
3. **Driver Errors**:
   - Check that the ChromeDriver version matches your installed Chrome browser.

---

## Future Enhancements

- Add support for more applications.
- Include custom wake words for activating the assistant.
- Expand functionality with additional APIs.





