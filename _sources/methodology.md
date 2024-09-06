# Methodology

![conceptual_diagram](_static/book_images/conceptual_diagram.svg)

**Deforum Music Visualizer** is built on *Google Colab* in order to freely host the demanding text-to-video generation process.

The independent *Gradio user interface* allows users to provide a Spotify URL and an audio track of the song. The Spotify API is then used to retrieve the track's Music Information Retrieval (MIR) data and album cover.

```{warning}
**Deforum Music Visualizer** can run without an attached audio track of the song, but the users are strongly encouraged to attach the version that is uploaded in Spotify. This ensures the optimal synchronization with the SpotifyAPI audio analysis and provides the best visualization results. Otherwise the tool tries to download the track via **[spotify_dl](https://github.com/SathyaBhat/spotify-dl)** and attempts to synchronize based on prevalent beats. This often leads to different song versions and unsyncrhonized results.
```

The album cover is processed using an image-to-text model to generate default prompts for the animation. After the user finalizes the prompts and selects the desired ```frames per second (fps)``` and ```duration```, the animation generation process begins.

Once the animation generation is complete, the user is provided with the final output visualization.
