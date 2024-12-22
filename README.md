# Text-to-Speech Converter Using Python

This is a simple Text-to-Speech (TTS) converter application built using Python's Tkinter library for the GUI and the `gTTS` (Google Text-to-Speech) library for converting text into speech. The user can input text into the provided entry field, and the application will read the text aloud using the system's audio.

## Features
- Input text into the entry field.
- Convert the input text to speech.
- Save the generated speech as an MP3 file.
- Play the generated MP3 file using the system's default audio player.

## Libraries Used
- **Tkinter**: A built-in Python library used for creating the GUI.
- **gTTS**: A Python library used to convert text to speech.
- **os**: A standard Python library used to interact with the operating system (to play the MP3 file).

## Requirements
Make sure you have the following libraries installed:
- `gTTS`

You can install the `gTTS` library using pip:

```bash
pip install gTTS
```

## Usage
1. Run the script:
   ```bash
   python main.py
   ```

2. The window will open with a text entry field.

3. Enter the text you want to convert to speech in the text field.

4. Click the "Start" button, and the text will be converted into speech.

5. The speech will be saved as `output.mp3` and played automatically.

## Example
Enter some text, e.g., `Heyy! How are you doing?`.  
![5](https://github.com/user-attachments/assets/07524568-5e59-4d3f-96b3-e9b2f6b63289)

Click the "Start" button to hear the text being read aloud.
(Sample mp3 audio file is uploaded in the repository)

## Troubleshooting
- If you encounter an issue with playing the MP3 file, ensure that your system's default audio player can open MP3 files.
