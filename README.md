AI Translator with OCR & Voice Input
Welcome to the AI Translator with OCR & Voice Input project! This Streamlit app allows users to translate text between different languages, extract text from images using Optical Character Recognition (OCR), and translate voice input. The app integrates several technologies such as Google Translate API, Google Text-to-Speech (gTTS), Tesseract OCR, and Speech Recognition to provide an easy-to-use, multilingual translation experience.

Features
Text Translation: Translate text between any supported languages with real-time feedback.
OCR (Optical Character Recognition): Extract text from images and translate it.
Voice Input: Capture voice input using a microphone, recognize speech, and translate it into the desired language.
Text-to-Speech: Convert translated text into speech and play the audio.
History: Keep track of past translations and their corresponding languages.
Technologies Used
Streamlit: For building the web application interface.
Googletrans: Python library for Google Translate API.
gTTS (Google Text-to-Speech): To convert text to speech.
pytesseract: OCR tool for extracting text from images.
SpeechRecognition: For voice-to-text conversion.
pyttsx3: Offline text-to-speech conversion.
Pillow (PIL): Image processing for OCR.
How to Use
Text Translation: Enter text in the input box and select source and target languages. The translated text will appear below.
OCR from Image: Upload an image with text, and the app will extract and display the text. It can also translate the extracted text.
Voice Input: Click the "Start Voice Recording" button, speak into the microphone, and the app will recognize and translate your speech.
Text-to-Speech: After the text is translated, you can listen to the translated text by clicking the audio button.
User Interface
Language Selection: You can choose both the source and target languages from a dropdown menu.
Text Area: Enter text for translation or view the translated text.
Buttons: For actions like swapping languages, starting voice recording, or viewing translation history.
OCR: Upload an image for text extraction and translation.
