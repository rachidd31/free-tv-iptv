# 📺 Onxy TV — Free Web IPTV & Live Stream Player

> **A sleek, modern, zero-backend web IPTV client and live television streaming player built for modern browsers.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-BFA46A?style=for-the-badge&logo=google-chrome)](https://rachidd31.github.io/free-tv-iptv/)
[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg?style=for-the-badge)](LICENSE)
[![Stream Engine](https://img.shields.io/badge/Streaming-HLS.js-blue?style=for-the-badge&logo=html5)](https://github.com/video-dev/hls.js/)
[![Architecture](https://img.shields.io/badge/Architecture-100%25%20Client--Side-brightgreen?style=for-the-badge)](index.html)

---

## 🧭 Overview

**Onxy TV** is a lightweight, zero-dependency single-page web player for watching free, publicly available broadcast television channels from around the world.

Powered by **HLS.js** and integrated with the community-maintained [iptv-org](https://github.com/iptv-org/iptv) index, it delivers instant playback with smart stream recovery, country/genre filtering, and full local playlist management.

---

## 🌐 Live Web Player (GitHub Pages)

Watch live TV directly in your browser with zero installation:

👉 **[https://rachidd31.github.io/free-tv-iptv/](https://rachidd31.github.io/free-tv-iptv/)**

---

## ✨ Features

* 🌍 **Global Channel Directory**: Browse thousands of free international broadcast channels with localized country names and flag emojis.
* ⚡ **High-Performance HLS Playback**: Powered by Hls.js with automated buffer management, adaptive bitrate support, and low latency.
* 🛡️ **Intelligent Stream Failover**: Automatic HTTP $\to$ HTTPS protocol upgrades and native video fallback when Hls.js encounters mixed-content or codec barriers.
* 🔍 **Instant Search & Filtering**: Filter by country, genre (News, Sports, Entertainment, Kids, etc.), or search channel names in real time.
* ⭐ **Favorites & Frequently Watched**: Save favorite channels and automatically track most-played stations in your browser (`localStorage`).
* ➕ **Custom M3U & Stream Injection**: Add your own custom `.m3u8` stream URLs or load custom M3U playlist files.
* ⬇️ **M3U Playlist Export**: Export your curated favorites or custom streams as an `.m3u` file compatible with VLC, Kodi, or Apple TV.
* 🖼️ **Picture-in-Picture (PiP) & Fullscreen**: Pop out video to float above other windows while multitasking.
* 🎨 **Luxury Dark UI**: Clean obsidian and champagne gold design with infinite scroll virtualization.
* 🚀 **100% Client-Side**: No backend server, no database, no registration required.

---

## 📁 Repository Structure

```
free-tv-iptv/
├── index.html       # Standalone live web player (GitHub Pages landing page)
├── onxy_tv.html     # Master application source
├── README.md        # Project documentation
├── LICENSE          # MIT License
└── .gitignore       # Git ignore rules
```

---

## 🚀 How to Run Locally or Deploy

### Option 1: GitHub Pages (1-Click Deployment)
1. Push this repository to GitHub.
2. Go to **Settings** $\to$ **Pages**.
3. Under **Build and deployment** $\to$ **Source**, choose **Deploy from a branch** (`main` / `/ (root)`).
4. Access your live TV player at `https://<username>.github.io/free-tv-iptv/`.

### Option 2: Run Locally
Since this is a pure static HTML5 application:
* **VS Code**: Right-click `index.html` $\to$ **Open with Live Server**.
* **Python Server**:
  ```bash
  python -m http.server 8000
  ```
  *(Then navigate to `http://localhost:8000`)*
* **Node.js**:
  ```bash
  npx serve .
  ```

---

## ⚖️ Legal Disclaimer

* **Onxy TV is an open-source client-side media player.** It does not host, broadcast, archive, or retransmit any video streams, audio streams, or media files.
* All channel links are parsed from public, freely accessible community playlists (such as `iptv-org`).
* Users are responsible for verifying that their streaming sources comply with local copyright laws and licensing terms in their respective jurisdictions.

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).
