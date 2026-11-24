# Streamed

A sleek, minimalist, single-file streaming web application.

[Visit Live Website: streamed.my.to](https://streamed.my.to)

---

## Features

- **Dedicated Theater Watch Page (`#watch`)**
  - Modern two-column cinema layout with an immersive 16:9 responsive player.
  - Complete episode and movie metadata: titles, ratings, release dates, and full plot synopses.
  - Native Share button with clipboard fallback and toast feedback.
  - Horizontally scrollable recommendations carousel.

- **Interactive TV Episode Sidebar**
  - **Quick Stepper Controls**: Seamless previous and next episode buttons with a live episode counter.
  - **Episode Cards**: High-definition TMDB snapshot stills, runtimes, and active "Now Playing" status.
  - **In-Place Playback**: Switch episodes instantly without full-page reloads.

- **TV Series Seasons and Episodes Showcase**
  - Dedicated episodes section directly on series detail pages (`#title/tv/:id`).
  - Episode cards with air dates, runtimes, episode numbers, and synopses.
  - One-click launch straight into the player.

- **Custom Dark Minimalist UI**
  - Custom floating season dropdowns that replace default browser select popups.
  - Polished frosted glass, smooth transitions, and high-contrast typography.
  - Fully responsive across mobile, tablet, and widescreen desktop displays.

- **Client-Side and Privacy-First**
  - **Zero backend required**: Runs completely in the browser via GitHub Pages.
  - **Local Storage Only**: TMDB API key, watch preferences, and history remain strictly on your device.

---

## Tech Stack

- **HTML5 & Vanilla JavaScript**: Fast, dependency-free single-page application (SPA) architecture.
- **Modern CSS3**: CSS Grid, Flexbox, Custom Properties, and frosted glass design (`backdrop-filter`).
- **TMDB API**: Global database for movies, TV series, actors, posters, and episode stills.

---

## Disclaimer

Streamed is an open-source project created strictly for educational and personal portfolio purposes. This website does not host, store, or distribute any video or copyrighted media files on its servers. All metadata and images are retrieved via the TMDB API, but Streamed is not officially endorsed or certified by TMDB.
