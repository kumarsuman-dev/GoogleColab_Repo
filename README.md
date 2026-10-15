# Hindi to English Speech Translation

## Project Overview
This project converts spoken Hindi into English speech using speech recognition, text tokenization, machine translation, and text-to-speech technology. It is implemented in Python using Google Colab.

## Project Workflow
1. **Hindi Speech Input:** Record Hindi speech using a microphone.
2. **Speech Recognition:** Convert the recorded audio into Hindi text using the Whisper model.
3. **Tokenization:** Convert Hindi text into tokens and numerical token IDs.
4. **Machine Translation:** Translate Hindi text into English using the NLLB-200 model.
5. **Speech Generation:** Convert the English translation into speech using Google Text-to-Speech (gTTS).
6. **Audio Output:** Play the generated English voice.

## Technologies Used
- Python
- Google Colab
- OpenAI Whisper
- Facebook NLLB-200
- Hugging Face Transformers
- NumPy
- SoundFile
- gTTS

## Installation
Install the required libraries in Google Colab:

```python
!pip install transformers sentencepiece sacremoses gTTS librosa soundfile
```

## How to Run
1. Open the project notebook in Google Colab.
2. Run the installation cell.
3. Load the speech recognition and translation models.
4. Allow microphone access.
5. Record a Hindi sentence.
6. View the recognized Hindi text, tokens, and numerical vector representation.
7. Read the English translation and listen to the generated English speech.

## Example

**Hindi Input:** मेरा नाम सुमन कुमार है।

**English Translation:** My name is Suman Kumar.

**Output:** English speech generated from the translated text.

*Note: Translation and speech recognition accuracy may vary depending on audio quality, pronunciation, and the models used.*

## Future Improvements
- Improve Hindi speech recognition accuracy.
- Add support for more Indian languages.
- Build a simple web interface.
- Improve translation quality and speech generation.

## Author
Suman Kumar

## License
This project is intended for educational and academic purposes.
