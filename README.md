# Chronos — Event Countdown

A responsive event countdown dashboard with:
- Unlimited events, categories, notes and accent colors
- Live countdown with only relevant time units
- Elapsed-time percentage progress (start date → event date)
- Dashboard cards and chronological timeline
- Monthly and yearly calendars
- LocalStorage persistence
- JSON export/import backup
- Dark/light theme toggle

## Run locally
Open `index.html` in a modern browser. No build tools or server required.

## Publish on GitHub Pages
Upload `index.html`, `style.css`, and `script.js` to the repository root, then enable GitHub Pages from repository Settings → Pages.

## Data storage
Events are stored in the current browser/device using LocalStorage. They are not automatically synced between users or devices. Export a JSON backup before clearing browser data or changing devices.

## Progress calculation
Progress percentage is calculated from each event's chosen **Countdown starts from** date/time to its **Event date & time**. The start date defaults to the time the event is created, but can be edited. Completed events show 100%.
