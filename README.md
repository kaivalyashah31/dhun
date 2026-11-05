# Dhun

Dhun is an independent, open-source music player PWA. It plays audio files that you import on your device and can optionally search and stream independent tracks through Jamendo's API after you configure your own Client ID.

## Run locally

Open `index.html` for a quick preview. For offline caching and install support, serve the folder on localhost or HTTPS:

```sh
npx serve .
```

On a phone, open the HTTPS site and choose **Add to Home Screen** (iOS Safari) or **Install app** (Android Chrome).

## Use Dhun

- Choose **Import your music** and select audio files from your device. Imported audio stays in this browser's IndexedDB; it is not uploaded to Dhun or a server.
- Search your imported library, play, pause, skip, seek, shuffle, and adjust volume.
- Like tracks and create playlists. Your profile name, likes, playlists, and Jamendo Client ID are saved in this browser.
- Optionally, create a Jamendo developer app, accept its API terms, and enter its Client ID in your Dhun profile settings. Dhun then offers catalog search and chillout discovery, with license links displayed for tracks. The API and each track's license terms still apply.

## Included

Responsive interface, local audio import and playback, IndexedDB media storage, likes and playlists, optional Jamendo search/playback, PWA manifest, and service worker.

## Limits

This is a personal music player, not a commercial global streaming catalog. It does not bundle copyrighted recordings, provide Google sign-in or cloud account sync, or store music on a server. Jamendo is an independent artist catalog and does not include all commercial releases. User-imported audio remains subject to the user's rights to play it.

Dhun has its own name and design and is not affiliated with Spotify.
