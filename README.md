# Spotify_spotipy
Using spotipy to make playlists with specific BPMs

Spotify used to have a running feature where it would play songs with a selected BPM based on your tastes. It was essentially like an unlimited discover weekly based around the tempo. Then they killed this feature. Thus, I was interested in making playlists of music I like or music I might like at a given tempo. 

One way to do this is by using the playlistmachinery website. I already leveraget this website to do just that. However, if you want to draw from many playlists, this can be very very tedious. Therfore I wanted to learn to use the spotify API through the spotipy python library and then generate these playlists. I'm not very good at this, so this is probably a very messy solution to the problem.

I used a jupyter notebook. I'm still learning all of this, so I'm wide open to improvements. I'll describe my choices within the notebooks.

There are two notebooks. One automatically generates masssive playlists at 10BPM intervals from 100-200. I use the other one to selectively generate playlists.
