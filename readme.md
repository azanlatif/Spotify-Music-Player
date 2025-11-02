
![Spotify Clone Banner](COVER.png)

# Spotify Clone

A web-based music player that mimics the basic functionality of Spotify. This project is built using HTML, CSS, and JavaScript. It dynamically loads music and playlists from a local directory structure, providing a seamless music listening experience.

## Features

- **Dynamic Music Library:** Automatically discovers and displays music playlists from the `songs` directory.
- **Playlist Display:** Each playlist is shown as a card with a cover image and description.
- **Music Playback:** Click on a song to play it.
- **Player Controls:** Standard controls including play, pause, next, and previous songs.
- **Seek Bar:** A visual representation of the current song's progress, which can be used to seek to different parts of the song.
- **Volume Control:** Adjust the volume or mute the audio.
- **Responsive Design:** The user interface is designed to be responsive and works on various screen sizes, with a hamburger menu for mobile navigation.

## Tech Stack

- **HTML5:** For the structure of the web application.
- **CSS3:** For styling the user interface, including a responsive layout with Flexbox and Grid.
- **JavaScript:** For all the client-side logic, including fetching songs, audio playback, and handling user interactions.

## Getting Started

To run this project locally, you need a local web server to serve the files, as the application uses `fetch` requests to load song data, which is restricted by CORS policy if you open the `index.html` file directly in the browser.

### Prerequisites

A simple local web server. You can use Python's built-in server, or a Node.js-based server like `live-server`.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/spotify-clone.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd spotify-clone
    ```
3.  **Start a local server.** For example:
    ```bash
    using the VS Code "Live Server" extension.
    ```

4.  **Open your browser** and go to `http://127.0.0.1:5500/` (or the address provided by your local server).

## Usage

- The main page displays the available playlists.
- Click on a playlist card to load the songs from that playlist into the library section on the left.
- Click on a song in the library to start playing it.
- Use the player controls at the bottom to manage playback.

## Folder Structure

The project is organized as follows:

```
.
├── css/
│   ├── style.css       # Main stylesheet
│   └── utility.css     # Utility classes
├── img/                # All static images and icons
├── js/
│   └── script.js       # Main JavaScript file
├── songs/              # Music library
│   ├── [Playlist Name]/
│   │   ├── cover.jpg   # Cover image for the playlist
│   │   ├── info.json   # Playlist metadata (title, description)
│   │   └── ... (song files).mp3
│   └── ...
├── index.html          # Main HTML file
└── readme.md           # This file
```

To add a new playlist, create a new folder inside the `songs` directory. Add your `.mp3` files, a `cover.jpg` for the album art, and an `info.json` file with the following format:

```json
{
    "title": "Your Playlist Title",
    "description": "A brief description of your playlist."
}
```

## Contributing

Contributions are welcome! If you have any suggestions or find any bugs, please open an issue or submit a pull request.

## License

This project is for educational purposes only. The code is not licensed for commercial use.

## Developer

### AZAN LATIF
