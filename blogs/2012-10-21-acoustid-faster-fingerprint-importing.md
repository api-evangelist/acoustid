---
title: "AcoustID: Faster fingerprint importing"
url: "https://blog.acoustid.org/posts/2012-10-21-acoustid-faster-fingerprint-importing/"
date: "2012-10-21"
feed_url: "https://blog.acoustid.org/index.xml"
---
Asynchronous importing of user submissions was always a big part of the AcoustID architecture. It makes things much easier to handle on the server side, allows database maintenance without turning the service to read-only mode (just delays the imports) and has many other benefits. However, people often wanted to get back AcoustIDs for fingerprints they just submitted.
