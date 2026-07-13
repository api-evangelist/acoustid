---
title: "Acoustid database dump available"
url: "https://blog.acoustid.org/posts/acoustid-database-dump-available/"
date: "2011-01-12"
feed_url: "https://blog.acoustid.org/index.xml"
---
I’ve finally written a script to take a consistent dump of the Acoustid database in the PostgreSQL tab-separated format used by the COPY command. I do not have any tools for importing it into PostgreSQL, so it has to be done manually by running SQL commands, but if anybody is interested in playing with the database, you can download it here (2.7G after compression using bzip2, 6.4G uncompressed). The data is licensed under a Creative Commons BY-SA 3.
