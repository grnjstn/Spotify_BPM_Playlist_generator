# Spotify_spotipy
Using spotipy to make playlists with specific BPMs

Spotify used to have a running feature where it would play songs with a selected BPM based on your tastes. It was essentially like an unlimited discover weekly based around the tempo. Then they killed this feature. Thus, I was interested in making playlists of music I like or music I might like at a given tempo. 

One way to do this is by using the playlistmachinery website. I already leveraged this website to do just that. However, if you want to draw from many playlists, this can be very very tedious. Therefore I wanted to learn to use the spotify API through the spotipy python library and then generate these playlists. I'm not very good at this, so this is probably a very messy solution to the problem.

I used a jupyter notebook. I'm still learning all of this, so I'm wide open to improvements. I'll describe my choices within the notebooks.

I'm currently sharing one notebook that automatically generates masssive playlists at 10BPM intervals from 100-200. 

I have a second notebook that I use to selectively generate playlists. I may also share that one. Both notebooks require you to first make a playlist in spotify as a destination for these playlists. The API can certainly generate new playlists, but I do not want to keep creating new ones. So then I would need to check for whether a plyalist exists already by name. Maybe I'll do this at some point. For now, the solutions provided here work for me.
