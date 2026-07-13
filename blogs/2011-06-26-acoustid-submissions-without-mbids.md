---
title: "Acoustid submissions without MBIDs"
url: "https://blog.acoustid.org/posts/acoustid-submissions-without-mbids/"
date: "2011-06-26"
feed_url: "https://blog.acoustid.org/index.xml"
---
I’ve released a new version of the Acoustid server that doesn’t require submissions to include MusicBrainz recording IDs. Applications can send textual metadata (track, artist, album, album artist, year, track number, disc number) instead and the server will try to match the tags to MusicBrainz by itself. The matching is actually not yet implemented, but the server is able to collect the data.
