# HTML Starter

A simple static HTML5 website template originally designed for Vercel, now running in Replit.

## Project Structure

- `index.html` — Main HTML page with content and styles
- `middleware.js` — Vercel Edge Middleware (adds security headers; not used in Replit)
- `package.json` — npm config with `serve` for local dev server

## Running the App

The app is served as static files using `serve` on port 5000.

```
npm start
```

## Deployment

Configured as a **static** deployment with `publicDir: "."`.
