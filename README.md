# Mood Melody :musical_note:

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Mood Melody is a web application that recommends music based on your detected mood. Using your webcam, the app captures your image, analyzes your facial expressions with a machine learning model to determine your emotion, and then suggests songs that match your vibe. Finally, you can groove to the recommended tunes using the Spotify API!

## :rocket: How it works

1.  :computer: Open Mood Melody in your browser.
2.  :camera: Grant access to your webcam.
3.  :thinking: The app captures your image and sends it to our emotion detection service.
4.  :magic: Our service analyzes your facial expression and determines your emotion.
5.  :notes: Based on your emotion, the app recommends a playlist or a selection of songs.
6.  :headphones: Enjoy the music using the Spotify API!

## :toolbox: Technologies Used

*   :atom: **Frontend:**
    *   React: A JavaScript library for building user interfaces.
    *   Tailwind CSS: A utility-first CSS framework for rapid UI development.
    *   @react-three/fiber: A React renderer for Three.js.
    *   react-webcam: A React component for capturing images from a webcam.
    *   axios: A promise-based HTTP client for making requests to the backend.
*   :snake: **Backend:**
    *   Python: The backend is built using Python.
    *   Machine Learning: A machine learning model is used to detect the user's emotion from their image.
    *   Flask: A micro web framework for Python.
*   :spotify: **API:**
    *   Spotify API: Used to play the recommended songs.

## :gear: Technical Aspects

Mood Melody is composed of two main components:

1.  **Frontend:** Developed with React and styled with Tailwind CSS, the frontend uses `react-webcam` to access your webcam and capture your image. `axios` is used to communicate with the backend emotion detection service and retrieve song recommendations.
2.  **Backend:** The Python-based backend service employs machine learning techniques to analyze your image and detect your emotion. It then returns the detected emotion along with a curated list of songs.

## :arrow_down: Installation

1.  Clone the repository: `git clone https://github.com/rakcoder/Music.git`
2.  Install the dependencies: `npm install` (for the frontend) and `pip install -r requirements.txt` (for the backend).
3.  Start the application: Follow the instructions in the `README.md` files of the `emotion-music-app` (frontend) and `python-emotion-service` (backend) directories.

## :eyes: Usage

1.  Open Mood Melody in your browser.
2.  Allow the application to access your webcam.
3.  The application will capture your image and recommend songs based on your detected emotion.
4.  Enjoy the music!

## :handshake: Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## :copyright: License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
