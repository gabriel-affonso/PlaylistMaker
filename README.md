# PlaylistMaker
A code meant to generate spotify playlists using OpenAI davinci motor
# Spotify Playlist Generator

This code is a prototype developed to demonstrate the integration of Spotify's platform with AI to create interesting and themed playlists. It utilizes the Spotipy library for Spotify integration and OpenAI's API for generating song suggestions.

## Prerequisites

Before running this code, you need to complete the following steps:

1. **Spotify Developer Dashboard**: Access the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) and create a new application to obtain the necessary credentials. Make note of the **Client ID**, **Client Secret**, and **Redirect URI**.

2. **OpenAI API Key**: Obtain an API key from OpenAI to use their text generation service. Make sure you have an OpenAI account and generate an API key.

## Setup

1. Clone the repository and navigate to the project directory.

   ```
   git clone https://github.com/your-username/spotify-playlist-generator.git
   cd spotify-playlist-generator
   ```

2. Install the required dependencies using pip.

   ```
   pip install -r requirements.txt
   ```

3. Open the `playlist_generator.py` file in a text editor.

4. Replace the following placeholders with your credentials:

   - Replace `''` with your Spotify **Client ID** within the `client_id` parameter of the `SpotifyOAuth` initialization.
   - Replace `''` with your Spotify **Client Secret** within the `client_secret` parameter of the `SpotifyOAuth` initialization.
   - Replace `''` with your Spotify **Redirect URI** within the `redirect_uri` parameter of the `SpotifyOAuth` initialization.
   - Replace `''` with your OpenAI **API Key** within the `openai.api_key` assignment.

## Usage

1. Run the `playlist_generator.py` file.

   ```
   python playlist_generator.py
   ```

2. Follow the prompts to specify the playlist details, such as the theme, number of songs, and playlist name.

3. The code will use the provided inputs to generate song suggestions and add them to a Spotify playlist.

## License

This code is developed under the free license of OpenAI as an experimental project. Feel free to modify, distribute, and use it as per your requirements. However, please note that the integration with Spotify's platform is subject to Spotify's terms and conditions.

## Future Developments

This prototype serves as a starting point for further developments in the integration of AI with the Spotify platform. We hope that this project inspires you to explore more exciting possibilities in this area. Contributions and feedback are always welcome!

If you have any questions or suggestions, please feel free to reach out. Happy playlist generating!
