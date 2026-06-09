# MD Pad

A free markdown editor PWA with live preview

Write, upload, download. No account needed

## Features

- Split-pane editor with live rendered preview (GFM)
- Drag and drop any `.md` file to open it
- Upload via button or `Ctrl+O`
- Download via button or `Ctrl+S`
- Auto-saves to localStorage every 500ms (survives refresh)
- Word, char and line count in the status bar
- Resizable divider between editor and preview
- Mobile toggle between editor and preview views
- PWA: installable with offline support via service worker
- Tab key inserts spaces

## Tech

- Single `index.html` with all CSS and JS inline
- [marked.js](https://marked.js.org/) for markdown parsing
- Service worker for offline caching
- Zero backend, zero accounts, zero tracking

## Use

Serve the folder with any static server:

```bash
npx serve . -p 3000
```

Or just open `index.html` in a browser

## License

MIT
