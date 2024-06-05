# Free-Scribe

Free-Scribe is a React-based web application for transcription and translation. It utilizes web workers to run machine learning models directly in the browser, ensuring efficient and real-time processing of audio files without needing to rely on server-side computations.

## Features

- **Real-Time Transcription**: Converts speech to text in real time.
- **Translation**: Translates the transcribed text into various languages.
- **Browser-Based Processing**: Utilizes web workers to run ML models directly in the browser for faster and more efficient processing.
- **User-Friendly Interface**: Built with React for a seamless user experience.

## Demo

Watch the demo video to see Free-Scribe in action:

[![Watch the demo](https://youtu.be/k6IaJwdXLy8)

*Click the image above to watch the demo video.*

## Installation

To get started with Free-Scribe, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/free-scribe.git
    cd free-scribe
    ```

2. **Install dependencies:**

    ```sh
    npm install
    ```

3. **Start the development server:**

    ```sh
    npm start
    ```

    This will start the app on `http://localhost:3000`.

## Usage

1. **Upload an audio file**: Click the upload button to select an audio file from your computer.
2. **Transcription**: The app will automatically transcribe the audio into text in real-time.
3. **Translation**: Select the desired language for translation. The transcribed text will be translated accordingly.

## How It Works

Free-Scribe leverages the power of web workers and modern web technologies:

- **React**: Provides a robust and efficient way to build the user interface.
- **Web Workers**: Offload the heavy lifting of running ML models to separate threads, ensuring the main thread remains responsive.
- **Machine Learning Models**: Uses pre-trained models for speech-to-text and translation tasks, which run entirely in the browser.
