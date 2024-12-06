# Language Translator App

This is a simple and interactive Language Translator App built using JavaScript and the Google Translation API. The app allows users to translate text between multiple languages in real-time with ease.

## Features

### User Interface (UI)
- **Text Input Area**: Users can input text to be translated.
- **Language Selection**: Dropdown menus for selecting the source and target languages.
- **Translate Button**: Initiates the translation process.
- **Translation Output**: Displays the translated text.

### Core Features
- **Text Input**: Supports text input in any language supported by the Google Translation API.
- **Language Selection**: Choose the source and target languages from a list of supported languages.
- **Real-Time Translation**: Translates text instantly by fetching data from the Google API.
- **Multiple Language Support**: The app supports a wide variety of languages for translation.

### Interactivity
- **Translation Process**: Click the "Translate" button to trigger the translation, which fetches the translated text via an API request.
- **Real-Time Feedback**: A loading spinner or animation is displayed during the translation process, offering real-time feedback while the text is being translated.

## Technologies Used
- **JavaScript**: Core functionality for interacting with the Google Translation API.
- **HTML/CSS**: For building the structure and styling the app's interface.
- **Google Translation API**: Powers the translation process.

## How to Use

1. **Input Text**: Enter the text you want to translate in the provided text box.
2. **Select Languages**: Choose the source and target languages using the dropdown menus.
3. **Translate**: Click the "Translate" button to see the translated text in the output area.
4. **View Results**: The translated text will be displayed instantly below the input area.

## Installation

To use this app locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SimouCode/Languge-Translator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd language-translator
    ```
3. Open `index.html` in your web browser to use the app.

## API Key Setup

1. To use the Google Translation API, you'll need to get your API key from [Google Cloud Console](https://console.cloud.google.com/).
2. After getting the API key, insert it into the JavaScript code where the API request is made to authenticate and fetch translations.

## Contributing

Feel free to fork this project, make improvements, or submit issues and pull requests. Contributions are welcome!

## License

This project is open source and available under the MIT License. See the [LICENSE](LICENSE) file for more details. 
