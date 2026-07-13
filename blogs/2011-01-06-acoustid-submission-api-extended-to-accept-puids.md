---
title: "Acoustid submission API extended to accept PUIDs"
url: "https://blog.acoustid.org/posts/acoustid-submission-api-extended-to-accept-puids/"
date: "2011-01-06"
feed_url: "https://blog.acoustid.org/index.xml"
---
As strange as it might sound, the Acoustid submission API can now also accept PUIDs instead of MBIDs . I had the idea of using PUIDs to help bootstrap the Acoustid database for a long time, but I avoided implementing it, because I was afraid of bringing all the PUID↔MBID matching errors to the database. The topic came up yesterday and I realized that with having the audio fingerprints, MBIDs and MusicBrainz metadata in the same database, I can pretty easily remove any suspicious matches.
