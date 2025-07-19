# shuffle_spotify_playlist
Pyhon script to create a copy of a playlist with all tracks shuffled.
Accesses the spotify API via spotipy package

Here's why this is useful:

When planning a party — whether for friends, colleagues, or clients — I usually take care of the music myself. I enjoy curating playlists and selecting songs that fit the occasion and mood. For me, music is too important to rely on AI-generated or generic playlists. I want the experience to feel intentional and personal.

However, I kept running into the same problem: after assembling a playlist of 80-120 songs, I'd notice that similar tracks or songs from the same artist often ended up grouped together. That's natural — it reflects the way we think while adding songs. But it doesn't make for a good listening experience.

Shuffle mode in Spotify seemed like a quick fix, but it caused another issue: when the playback is stopped (e.g. during a dinner or speech) and resumed later, Spotify doesn't remember which songs have already been played. As a result, some tracks repeat, while others don't get played at all.

To avoid this, I wanted a way to shuffle the playlist once and then play it in regular, sequential mode — ensuring all songs are played once, in a good order, without repetition. Doing this manually for large playlists is tedious and time-consuming.

That's why I wrote a small Python script in a Jupyter Notebook to automate the process. It connects to your Spotify account, takes a playlist, shuffles it once, and saves the shuffled version as a new playlist. This gives you a great base to start from — and you can still reorder a few songs manually if you like.
