# Crown — Lagos-first restaurant crowns MVP

A mobile-first PWA prototype for a Lagos-first restaurant social-ranking concept.

## MVP
- Search demo restaurant cards by name, cuisine, and neighbourhood.
- Crown one restaurant per cuisine; crowning a different one replaces the previous champion.
- Personal court persisted in browser localStorage.
- Share the full court or a crowned restaurant using native share or clipboard fallback.
- Open restaurant searches in Google Maps via Maps URLs.
- Installable PWA shell and basic service worker.

## Important limitations
Restaurant cards are demo/sample data, not verified endorsements or live Google Places results. This prototype has no accounts, cloud sync, public profiles, friend graph, backend, or live Places API integration. No Google API key is required.

## Run locally
Serve the project over localhost or HTTPS (needed for service-worker/PWA features), for example:

```bash
python -m http.server 4173
```

Then open `http://localhost:4173`.

## Next step
Add accounts and shareable public courts, then consider Places API integration after checking budget and Google Maps Platform terms.