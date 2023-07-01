# SPOTIFY-CLONE

This is a Spotify clone project created as part of a web development course. It aims to replicate some of the key features and user interface elements of the popular music streaming platform, Spotify.

## Features

- User authentication: Users can create an account, log in, and log out.
- Search functionality: Users can search for songs, albums, and artists.
- Music playback: Users can play, pause, and skip songs.
- Playlist management: Users can create and manage their playlists.
- Favorite tracks: Users can mark songs as favorites and access them easily.
- Responsive design: The application is designed to work seamlessly across different devices and screen sizes.

## Technologies Used

- Front-end: HTML, CSS, JavaScript
- Back-end: Node.js, Express.js
- Database: MongoDB
- Spotify Web API: Used for fetching music data and playback control

## Installation

1. Clone the repository: `git clone https://github.com/abokmadaki/spotify-clone.git`
2. Navigate to the project directory: `cd spotify-clone`
3. Install the dependencies: `npm install`
4. Set up the environment variables:
   - Create a `.env` file in the root directory
   - Add the following variables:
     ```
     SPOTIFY_CLIENT_ID=your_spotify_client_id
     SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
     MONGODB_URI=your_mongodb_uri
     SESSION_SECRET=your_session_secret
     ```
   - Replace the placeholder values with your own credentials.
5. Start the development server: `npm start`
6. Open your browser and visit: `http://localhost:3000`

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m "Add feature"`
4. Push the changes to your forked repository: `git push origin feature-name`
5. Open a pull request in the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- The Spotify API for providing the music data and playback functionality.
- The web development course for inspiration and guidance in creating this project.

## Contact

If you have any questions or suggestions, feel free to contact the project maintainer at [abokistifanusmadaki@gmail.com](mailto:abokistifanusmadaki@gmail.com).
