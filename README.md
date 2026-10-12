# 7awel Admin Dashboard

Interactive prototype of the 7awel Admin Dashboard (KASHY / 7awel · Syria).

## Run it
1. Download this repository as a ZIP and unzip it (or clone it).
2. Serve the folder with any static web server — the page loads sibling scripts, so opening the file directly from disk may be blocked by the browser:
   - Python: `python3 -m http.server 8080`
   - Node: `npx serve .`
   - VS Code: "Live Server" extension
3. Open `http://localhost:8080/` — `index.html` is the prototype.

## Files
- `index.html` — the prototype (template + logic in one file)
- `support.js` — runtime that renders the template

Sign in as Super Admin or Agent / Store from the login screen (any PIN).

## Notes
- Data is sample data; nothing is sent anywhere.
- State such as the active page, language and published banners is kept in the browser's local storage.
