# Dhun

Dhun is an original, responsive music player prototype. It is a standalone web app that can be installed on a phone as a Progressive Web App when hosted over HTTPS.

## Run locally

Open `index.html` for a quick preview. For the installable offline app, serve this folder over HTTP (the service worker is enabled on HTTP localhost and HTTPS):

```sh
npx serve .
```

Open the local URL in a modern browser. On a phone, deploy the folder to an HTTPS host, visit the URL, then choose **Add to Home Screen** (iOS Safari) or **Install app** (Android Chrome).

## Included

- Responsive desktop and mobile layouts
- Search across the included demo catalog
- Local liked tracks, profile name, and playlist names (stored in this browser)
- Player controls, progress, shuffle, repeat, and volume controls
- Original synthesized tones for demo playback
- PWA manifest and service worker for offline interface caching

## Not connected yet

The included tracks are fictional catalog entries and the player produces short synthesized demo tones. There are no commercial recordings. A world catalog requires licenses from rights holders and a streaming backend/CDN. Google sign-in needs OAuth configuration and a secure identity backend. User accounts, cross-device sync, production playback, and a hosted phone install require those services.

This project is an independent product concept with its own Dhun name and visual design; it is not affiliated with Spotify.
