# To‑Do List (HTML/CSS/JS + LocalStorage)

A lightweight to‑do list app that works entirely in the browser with persistent storage via `localStorage`.

## Features
- Add tasks
- Edit task titles inline
- Delete tasks
- Toggle complete/incomplete
- Clear completed or clear all
- Persists to `localStorage`

## Getting Started

### Option 1: Open directly
1. Double‑click `index.html` to open in your browser.
2. Start adding tasks.

### Option 2: Serve locally (recommended)
Some browsers impose stricter restrictions for `file://` pages. Serving via a local server avoids that.

- Using PowerShell in this folder:
  ```powershell
  # Python 3
  python -m http.server 5173
  # or Node (if installed)
  npx serve -l 5173 . --single --yes
  ```
  Then open `http://localhost:5173`.

## Project Structure
```
TO-DO-LIST/
├─ index.html     # App markup

```

## Notes
- Data key: `todo.tasks.v1` in `localStorage`.
- Tasks are stored as: `{ id, title, completed, createdAt }`.

## Optional: Backend
This app is designed to be client‑only. If you’d like a backend later (Node.js + Express), we can add simple REST endpoints to persist tasks to a file or database.



