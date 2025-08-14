# Harry Potter Audio

This tries to build a tool to replicate [thesocialgeekfamily from TikTok](https://www.tiktok.com/@thesocialgeekfamily/video/7506354369470811422). You can choose from Easy (15s), Medium (10s), Hard (5s), and Impossible (1s) and get a random clip from one of the 8 movies. You have to guess which one it belongs to.

<img width="1070" height="531" alt="preview" src="https://github.com/user-attachments/assets/67f42763-b8f2-4cc0-b634-ff97d092ef50" />

## Installation

### Web App
Create `config.local.js` and fill it with the movies pointing to Plex.
```
window.MOVIES = [
  {
    "title": "Harry Potter and the Sorcerer's Stone",
    "year": "2001",
    "duration": 9530634,
    "partId": "67718",
    "url": "http://<ip>:<port>/library/parts/67718/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
...
];
```

## Running

### Web App
Just drag and drop the `index.html` file into your browser and you're good to go!
