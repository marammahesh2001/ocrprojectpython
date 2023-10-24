# Image to Sound Converter

This script converts text found in an image file into an audio file using the Google Text-to-Speech (gTTS) library. The text extraction from the image is performed using the pytesseract library, and the image processing is handled with the PIL library.

## Setup

To run the script, you will need to install the necessary dependencies:

- Install the required Python packages:
  ```
  pip install Pillow
  pip install pytesseract
  pip install gTTS
  ```

- Ensure that Tesseract OCR is installed on your system. You can download it from [here](https://github.com/tesseract-ocr/tesseract).

## Usage

1. Place the image file you want to convert in the same directory as the script.

2. Adjust the image file name in the `convert_to_sound` function call to match the name of your image file.

3. Run the script using the following command:
   ```
   python script_name.py
   ```

The script will process the image, extract the text, convert it to speech, and save the audio file as `sound.mp3` in the same directory.

## Dependencies

- PIL (Python Imaging Library): Used for image processing.
- pytesseract: Used for text extraction from images.
- gTTS (Google Text-to-Speech): Used for text-to-speech conversion.
- os: Used for system-related operations.

