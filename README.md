# Harry Potter Audio

This tries to build a tool to replicate [thesocialgeekfamily from TikTok](https://www.tiktok.com/@thesocialgeekfamily/video/7506354369470811422). You can choose from Easy (15s), Medium (10s), Hard (5s), and Impossible (1s) and get a random clip from one of the 8 movies. You have to guess which one it belongs to.

<img width="1070" height="531" alt="preview" src="https://github.com/user-attachments/assets/67f42763-b8f2-4cc0-b634-ff97d092ef50" />

## Installation

Create `config.local.js` with your Plex server address, token, and movie metadata:

```js
window.TOKEN = "YOUR_PLEX_TOKEN";
window.IP = "https://YOUR_SERVER.plex.direct:PORT";
window.MOVIES = [
  {
    title: "Movie title",
    year: "2001",
    duration: 9500000,
    credits: 9000000,
    partId: "YOUR_PLEX_PART_ID",
    poster: "https://example.com/poster.jpg"
  }
];
```
