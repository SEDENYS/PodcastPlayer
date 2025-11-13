


<div align="center">
  <img src="public/podcast-icon-512.png" alt="Podcast Player Logo" width="140" />
  <h1>Podcast Player</h1>
  <p>Your simple and clean web-based podcast player powered by Podcast Index.</p>

  <a href="https://sedenys.github.io/PodcastPlayer/">
    <b>🌐 Live Demo</b>
  </a>
</div>


---

## 🎧 Overview

Podcast Player is a lightweight web app that lets you search podcasts, browse episodes, build a listening queue, and play them directly in the browser.
It also supports **PWA installation**, offline loading, and automatic progress saving — everything runs smoothly without extra clutter.

---

## 🚀 Features

* **Podcast Search** — find shows by title or keyword
* **Episode Browser** — open any podcast to explore its episodes
* **Audio Playback** — built-in player with play/pause, seeking, and skip
* **Queue System** — add episodes and listen in order
* **Progress Saving** — restores your last played episode and position
* **PWA Installation** — install the app to your phone or desktop
* **Offline Support** — Service Worker caches core assets

---



## 📦 Installation (Local)

```bash
git clone https://github.com/sedenys/PodcastPlayer.git
cd PodcastPlayer
npm install
```

Create a `.env` file in the root:

```
AUTH_KEY=your_api_key
SECRET_KEY=your_api_secret
USER_AGENT=your_app_name
API_ENDPOINT=https://api.podcastindex.org/api/1.0
```

Run the server:

```bash
npm start
```

App will be available at:

👉 **[http://localhost:3000](http://localhost:3000)**

---

## 🌐 Deployment

### 🔹 GitHub Pages (Static UI)

Live version:
**[https://sedenys.github.io/PodcastPlayer/](https://sedenys.github.io/PodcastPlayer/)**

### 🔹 Node.js Hosting (Render, etc.)

1. Fork repository
2. Connect to Render
3. Add environment variables
4. Deploy

Render handles build & hosting automatically.

---

## 🛠 Tech Stack

| Layer    | Technologies               |
| -------- | -------------------------- |
| Frontend | HTML, CSS, JavaScript      |
| Backend  | Node.js, Express           |
| API      | Podcast Index              |
| Storage  | LocalStorage               |
| PWA      | Service Worker + Cache API |
| Hosting  | GitHub Pages / Render      |

---

## 📚 How to Use

1. Enter a search term to find podcasts
2. Select a podcast → view episodes
3. Pick an episode → press Play
4. Add episodes to your queue
5. Install as PWA for a native-like feel

---

## 🙌 Credits

* **Podcast Index** — open podcast database
* **Flaticon/Custom Icon** — project logo
* **GitHub Pages / Render** — hosting

