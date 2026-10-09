# Timeline Keeper

A single-file timeline for fantasy worlds with custom calendars. Built for the Ashen Chronicle (Scarred Lands) campaign.

Open `index.html` in a browser, or serve the repository with GitHub Pages. There is no build step and nothing to install.

## Features

- **Custom calendars per world**: any months and days, festival days, custom weekdays, leap rules, eras. Presets for Scarred Lands, Harptos, Gregorian and a blank calendar.
- **Timeline view**: zoom from centuries to single days, moments as pins with icons, periods as lanes, milestone lines and shaded bands, a "Now" marker and session markers.
- **Month view**: a grid of the current month with your weekdays.
- **Editing on the timeline**: click the axis to add a moment, drag along it to add a period, drag events to move them, drag period ends to resize. Dates snap to the zoom level.
- **Characters**: story lines with appearances on them, a fixed name column with ages, life phases, collapse, follow and highlight.
- **Events**: date precision (day, month or year) and "c." for approximate dates, categories, locations, sessions, tags, links, cause and effect relations, recurring events, and Markdown descriptions.
- **DM tools**: secret events, DM notes and a Player view that hides both, session log, date calculator.
- **Bookmarks**: save up to 9 places and zoom levels, jump back with one key, and go back after a jump. Bookmarks can be named in the Bookmarks list.
- **Filters**: show only one category, toggle categories, filter by location, session and type, and search.
- **Data**: saved in the browser (localStorage), JSON backup and import, CSV export (UTF-8 with BOM, `^` delimiter), Markdown export for Notion, PNG image of the timeline, undo with Ctrl+Z.

## Data

- `index.html` contains the Ashen Chronicle as exported on 7 Oct 2026, plus Syreen Haven. A new browser starts from that data.
- Your changes are stored in the browser you use. To move them to another browser or device, use **Data → Copy JSON** and **Import**.
- `data/ashen-chronicle-backup-2026-10-07.json` is the original export, kept as a backup.

## Shortcuts

| Key | Action |
| --- | --- |
| `?` | Help: how the timeline works |
| `N` | New event |
| `M` | Switch timeline / month view |
| `P` | Player view |
| `F` | Fit all events |
| `.` | Jump to now |
| `+` / `−` | Zoom |
| `←` / `→` | Pan |
| `Shift+1`…`9` | Save the current view as a bookmark |
| `1`…`9` | Jump to a bookmark |
| `Backspace` | Go back to the previous view |
| `Ctrl+Z` | Undo |
