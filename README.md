# SpeechToText
# Speech to Text Translation and Transliteration Website

This repository contains the code for a web application that utilizes the Whisper API from OpenAI to perform speech-to-text translation and transliteration. The Whisper API is a powerful tool that allows you to convert spoken language into written text.

## Features

- **Speech to Text Translation**: The web application provides a user-friendly interface where users can upload audio files or record their voice directly to convert spoken language into written text.
- **Transliteration**: The application also supports transliteration, which means it can convert the text from one script or writing system to another. This feature is particularly useful for translating text into different phonetic representations or alphabets.
- **Multiple Language Support**: The Whisper API supports a wide range of languages, allowing users to transcribe and transliterate speech in various languages.
- **Easy Integration**: The application is built using the Whisper API from OpenAI, making it simple to integrate into other projects or systems.

## Getting Started

To get started with this application, follow these steps:

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/your-username/speech-to-text-translator.git
   ```
2. Create an account on the OpenAI platform and obtain an API key for the Whisper API.
3. In the project directory, create a file named `.env` and add your API key as follows:
   ```
   API_KEY=your-api-key
   ```
4. Install the project dependencies by running the following command:
   ```
   npm install
   ```
5. Start the web application by running the following command:
   ```
   npm start
   ```
   This will launch the application on `http://localhost:3000`.

## Usage

1. Access the web application by navigating to `http://localhost:3000` in your web browser.
2. Choose your preferred language for speech-to-text translation.
3. Click on the microphone button to start recording or upload an audio file using the provided interface.
4. Once the recording or file upload is complete, the application will process the audio and display the transcribed text.
5. If desired, you can select the transliteration option to convert the transcribed text into a different script or writing system.
6. Copy the resulting text or perform additional actions as needed.

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Create a pull request to merge your changes into the main repository.

Please ensure that your code follows the existing coding style and includes appropriate documentation.

## License

This project is licensed under the [MIT License](LICENSE).

## Disclaimer

This project is a demonstration of using the Whisper API from OpenAI for speech-to-text translation and transliteration. It is provided as-is and may not be suitable for production environments. OpenAI is not responsible for any issues or liabilities that may arise from the use of this project.
