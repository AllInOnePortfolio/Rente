# Renté

A peer-to-peer clothing rental app — browse, list, and book rentals between
users. Single-file static PWA (HTML/CSS/JS, no build step, no backend).

## Screens

- **Onboarding** — first-run welcome
- **Home** — greeting, wallet chip, search bar, category chips, trending/featured listings
- **Search** — browse and filter listings
- **Item detail** — photo carousel, price, owner info, reviews
- **Booking flow** — multi-step booking with date selection
- **Booking detail** — status tracking (`requested → confirmed → active → return_pending → completed`, or `declined`/`cancelled`)
- **List item** — create a new listing with photos and tags
- **Inbox / Chat** — messaging between renter and owner
- **Wallet** — balance and transactions
- **Notifications**
- **Favorites**
- **Profile / Edit profile** — stats, reviews, listings

## Running locally

It's a single static HTML file with no dependencies — just open `index.html`
in a browser, or serve the folder with any static file server.

Supports light/dark mode (via `prefers-color-scheme`) and is installable as
a PWA (`apple-mobile-web-app-capable`).
