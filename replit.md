# MeetHer — Dating Profile Directory

A clean, modern dating profile directory for verified adult women. Built as a pure static site (HTML, CSS, vanilla JS).

## Project Structure

- `index.html` — Profile grid directory (2 cards per row)
- `profile.html` — Individual profile detail page (served at `/profile?id=N`)
- `styles.css` — All styles: light/dark mode, responsive layout, card animations
- `profiles.js` — Profile data array (add/edit profiles here)
- `package.json` — Uses `serve` to run a local static file server on port 5000

## Features

- 2-column profile card grid with photo, name, age, location, bio
- Individual profile pages with photo gallery, bio, interests, WhatsApp contact
- Dark / light mode toggle (persisted in localStorage)
- Mobile-first responsive layout
- Smooth hover animations
- 18+ adult disclaimer
- "Contact on WhatsApp" button with pre-filled message

## Running the App

```
npm start
```

Serves all static files on port 5000.

## Adding Profiles

Edit `profiles.js` and add an entry to the `profiles` array with:
- `id`, `name`, `age`, `location`, `bio`, `interests[]`
- `photo` (main card photo URL)
- `photos[]` (gallery: 3 photos)
- `whatsapp` (number without `+`, e.g. `"12125550101"`)

## Deployment

Configured as a **static** deployment with `publicDir: "."`.
