[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17Z-UW9ybR113xKxOKK88Wcfsl621wQzM#scrollTo=UuttUY-t-gtd)

# DeforumMusicVisualizer
DeforumMusicVisualizer aims to enhance your listening experience by creating dynamic and creative visualizations based on your favorite music tracks. Utilizing [StableDiffusion Deforum](https://github.com/deforum-art/deforum-stable-diffusion) and the [Spotify API](https://developer.spotify.com/documentation/web-api), it generates captivating visuals synchronized with the audio analysis of your tracks, based on their album cover.

  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <p align="center">
    <img src="example_gifs/Funkdoobiest%20-%20Rock%20On.jpg" alt="Funkdoobiest - Rock On / Album Cover" width="256" height="256">
    <img src="example_gifs/Funkdoobiest%20-%20Rock%20On.gif" alt="Funkdoobiest - Rock On" width="256" height="256">
    </p>
  </div>

  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <p align="center">
    <img src="example_gifs/Herbie%20Hancock%20-%20Actual%20Proof.jpg" alt="Herbie Hancock - Actual Proof / Album Cover" width="256" height="256">
    <img src="example_gifs/Herbie%20Hancock%20-%20Actual%20Proof.gif" alt="Herbie Hancock - Actual Proof" width="256" height="256">
    </p>
  </div>

  <div style="display: flex; align-items: center;">
    <p align="center">
    <img src="example_gifs/Soundgarden%20-%20Burden%20In%20My%20Hand.jpg" alt="Soundgarden - Burden In My Hand / Album Cover" width="256" height="256">
    <img src="example_gifs/Soundgarden%20-%20Burden%20In%20My%20Hand.gif" alt="Soundgarden - Burden In My Hand" width="256" height="256">
    </p>
  </div>

## Instructions for Obtaining and Adding Spotify API Tokens

To use the MusicVisualizer, follow these steps to obtain and add Spotify API tokens as secrets in your Colab notebook:

1. **Get Client ID and Client Secret:**
   - Follow the steps provided [here](https://developer.spotify.com/documentation/web-api/tutorials/getting-started) to obtain the spotify client id and spotify client secret.

2. **Add the tokens as google colab secrets**
   - Open the google colab notebook and click on 'Secrets'->'Add new secret' options on the top left.
   - Create two secrets with the name 'SPOTIPY_CLIENT_ID' and 'SPOTIPY_CLIENT_SECRET' where you should copy the spotify tokens.
   - This will ensure the privacy of the spotify tokens while running the notebook.
  <div style="display: flex; align-items: center;">
    <p align="center">
    <img src="colab_secrets.jpg" alt="Google Colab Secrets" width="256" height="256">
    </p>
  </div>
<p align="center">
  <img width="460" height="300" src="colab_secrets.jpg">
</p>

3. **Ready to go**
   - You are now ready to start using the notebook and visualize your favourite tracks.
