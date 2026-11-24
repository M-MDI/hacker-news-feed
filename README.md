# Hacker News Feed

A browser-based reader for the public Hacker News API. Browse top, new, and best stories, along with Ask HN, Show HN, and job posts. The app loads more stories as you scroll and offers a refresh when new stories are available.

## Run locally

From the repository root, start a static file server with Python 3.

```sh
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000). The page needs an internet connection to fetch stories.

## Files

- `index.html` defines the feed and category tabs.
- `fetch.js` fetches and renders stories.
- `style.css` styles the interface.
