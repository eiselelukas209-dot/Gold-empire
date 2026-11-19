# Gold Empire

A local, offline casino and life simulator built as a single-page HTML app.

## Lokal starten

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Online veröffentlichen

The repository uses GitHub Pages. Push to `main`; the included workflow publishes the site automatically.

## Speicherung

Progress is stored locally in the browser using `localStorage`, IndexedDB and JSON backups.
Browser data is only persistent on the same device and browser. Clearing browser data or changing devices may remove or separate progress.
