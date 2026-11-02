# Georgia Trip POC

A single-page, Hebrew (RTL) overview of a 7-day trip to Tbilisi, Georgia.

## Files

- `itinerary.md` – source trip notes (Hebrew). The only source of facts for the page.
- `index.html` – self-contained page (inline CSS, no external dependencies) with:
  - Header with trip title and key facts
  - Budget summary
  - Day-by-day itinerary cards
  - Kosher / Chabad info, plus the travel advisory note

## Usage

Open `index.html` directly in any modern browser. No build step or server needed.

## Updating

When `itinerary.md` changes, update the matching section in `index.html` by hand.
Only use facts stated in `itinerary.md`; don't add prices or details that aren't there.
