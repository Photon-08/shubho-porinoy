# Indranil & Shaibalini — Shubho Bibaho

A responsive, frontend-only Bengali wedding invitation website for **Indranil & Shaibalini**, dated **7 December 2026**. The design blends storybook warmth, Bengali script, paper-like texture, sindoor red, muted gold, personal story cards, a photo gallery, wedding events, countdown, and WhatsApp RSVP.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Personalize the website
Open `index.html` and edit the `COUPLE` object near the bottom:
- `personOne` and `personTwo`
- `weddingDateText`
- `weddingDate` (local time in `YYYY-MM-DDTHH:MM:SS`)
- `rsvpWhatsApp` (country code + digits only, e.g. `919876543210`)

Replace bracketed event details and story placeholders with your real story and venue information.

## Add your photos
Create an `assets` folder beside `index.html` and add these image files:
- `our-first-photo.jpg`
- `a-day-together.jpg`
- `wedding-planning.jpg`

The gallery automatically shows a designed placeholder if a file is missing. Use your own photographs and make sure you have permission from anyone pictured.

## Frontend-only behavior
No backend or database is used. RSVP opens WhatsApp with a prefilled message. It does not save guest responses. Event map links open Google Maps after you replace the placeholder venue addresses.

Google Fonts are loaded online; local system fonts act as fallbacks.
