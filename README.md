# Audio Language Detection
## Overview
This project provides a Python script for detecting the language of spoken words in an audio file or through microphone input. It utilizes the speech_recognition, langdetect, and googletrans libraries for recognizing speech, detecting language, and translating text.

## Requirements
Python 3.x\
speech_recognition\
langdetect\
googletrans\

You can install the required libraries using pip:

```bash
pip install SpeechRecognition langdetect googletrans==4.0.0-rc1
```

## uses
### detect_language_from_audio(audio_file)
This function detects the language of spoken words from an audio file or microphone input.\
Parameters\
audio_file (str): Path to the audio file. If an empty string is provided, the script will use the microphone for input.\
Returns\
language (str): Detected language code (e.g., 'en' for English, 'fr' for French).

### translate_to_oriLanguage(text)
This helper function translates the input text to its original language.\

Parameters\
text (str): Text to be translated.\
Returns\
translated.text (str): Translated text.

## Notes
Ensure your internet connection is stable as the speech recognition and translation functionalities require online services.\
Handle exceptions properly to avoid unexpected crashes.



