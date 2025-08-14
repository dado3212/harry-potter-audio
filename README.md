# Harry Potter Audio

This tries to build a tool to replicate [thesocialgeekfamily from TikTok](https://www.tiktok.com/@thesocialgeekfamily/video/7506354369470811422). You can choose from Easy (15s), Medium (10s), Hard (5s), and Impossible (1s) and get a random clip from one of the 8 movies. You have to guess which one it belongs to.

<img width="1070" height="531" alt="preview" src="https://github.com/user-attachments/assets/67f42763-b8f2-4cc0-b634-ff97d092ef50" />

## Installation
Create `config.local.js` and fill it with the movies pointing to Plex (will need to update url and poster fields).
```
window.MOVIES = [
  {
    "title": "Harry Potter and the Sorcerer's Stone",
    "year": "2001",
    "duration": 9530634,
    "credits": 9035000,
    "partId": "67718",
    "url": "http://<ip>:<port>/library/parts/67718/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
  {
    "title": "Harry Potter and the Chamber of Secrets",
    "year": "2002",
    "duration": 9656234,
    "credits": 9102000,
    "partId": "67837",
    "url": "http://<ip>:<port>/library/parts/67837/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
    {
    "title": "Harry Potter and the Prisoner of Azkaban",
    "year": "2004",
    "duration": 8502239,
    "credits": 7794000,
    "partId": "67734",
    "url": "http://<ip>:<port>/library/parts/67734/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
  {
    "title": "Harry Potter and the Goblet of Fire",
    "year": "2005",
    "duration": 9425541,
    "credits": 8624000,
    "partId": "67790",
    "url": "http://<ip>:<port>/library/parts/67790/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
  {
    "title": "Harry Potter and the Order of the Phoenix",
    "year": "2007",
    "duration": 8294506,
    "credits": 7703000,
    "partId": "67735",
    "url": "http://<ip>:<port>/library/parts/67735/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
  {
    "title": "Harry Potter and the Half-Blood Prince",
    "year": "2009",
    "duration": 9211925,
    "credits": 8631000,
    "partId": "67759",
    "url": "http://<ip>:<port>/library/parts/67759/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
  {
    "title": "Harry Potter and the Deathly Hallows: Part 1",
    "year": "2010",
    "duration": 8765311,
    "credits": 8081000,
    "partId": "67836",
    "url": "http://<ip>:<port>/library/parts/67836/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
  {
    "title": "Harry Potter and the Deathly Hallows: Part 2",
    "year": "2011",
    "duration": 7826953,
    "credits": 7082000,
    "partId": "67828",
    "url": "http://<ip>:<port>/library/parts/67828/file?download=1&X-Plex-Token=<token>",
    "poster": "<poster.jpg>"
  },
];
```
