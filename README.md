# AcoustID

AcoustID is an open-source audio fingerprinting service providing a REST API for identifying music tracks by audio fingerprint and linking results to MusicBrainz metadata records. Built on the Chromaprint library, it offers a crowdsourced fingerprint database free for non-commercial use, with commercial plans available through AcoustID OÜ.

## Links

- **Website:** https://acoustid.org/
- **API Documentation:** https://acoustid.org/webservice
- **GitHub Organization:** https://github.com/acoustid
- **Blog:** https://blog.acoustid.org/
- **Commercial Pricing:** https://acoustid.biz/
- **X (Twitter):** https://twitter.com/acoustid

## API

The AcoustID Web Service API is available at `https://api.acoustid.org/v2` and provides:

- **Lookup** — identify a music track by Chromaprint fingerprint or AcoustID track ID
- **Submit** — contribute a new fingerprint to the crowdsourced database
- **Submission Status** — check the processing status of a submitted fingerprint
- **List by MBID** — retrieve AcoustIDs linked to a MusicBrainz recording ID

All requests require an application API key (`client` parameter) obtained by registering at https://acoustid.org/new-applications. Fingerprint submission additionally requires a user API key.

Responses are available in JSON (default), JSONP, and XML. GZip compression is supported on POST request bodies.

## Plans and Pricing

- **Free** — Non-commercial and open source use at no cost, limited to 3 requests/second
- **Small** — €50/month for 1 million searches, no rate limiting
- **Medium** — €100/month for 15 million searches, no rate limiting
- **Large** — €500/month for 150 million searches, no rate limiting
- **Custom** — Contact info@acoustid.biz for tailored plans

All commercial plans include a free trial covering the first 10,000 searches.

## Repository Contents

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/acoustid-plans-pricing.yml` — Plan and pricing details
- `rate-limits/acoustid-rate-limits.yml` — Rate limiting policies
- `finops/acoustid-finops.yml` — FinOps cost optimization guidance
