# Conference Tracker

## Overview
This is a **dummy** single-file conference tracker, designed for quick and lightweight tracking of conferences and their call-for-paper (CFP) deadlines. Everything runs in **a single HTML file**, leveraging **local storage** for persistence.

![](/img.png)

## Features
- **Single-file, no setup required** – Just open the HTML file.
- **Tracks conferences** – Save URLs and CFP deadlines.
- **Data persistence** – Uses browser **local storage**.
- **Import/Export** – Share or migrate your conferences.
- **Lightweight** – No frameworks, just pure HTML, CSS, and JS.

## How It Works
1. **Paste a conference URL**.
2. **Enter the CFP deadline**.
3. **Click Add** – The conference gets saved.
4. **View your list** – Countdown until the deadline.
5. **Edit/Delete as needed**.
6. **Export your list** – Save a `.json` backup.
7. **Import** – Restore from a previous export.

## Technical Details
- **Frontend only** – No backend required.
- **LocalStorage API** – Stores data persistently.
- **Fetch API** – Retrieves conference titles from URLs.
- **CORS handling** – Uses a public proxy (`allorigins.win`).
- **Mobile-friendly UI** – Optimized for desktop & mobile.

## How to Use
1. Open `index.html` in a browser.
2. Start adding conferences!
3. To export, click **Export All**.
4. To import, click **Import** and select a `.json` file.

## Limitations
- Some conference websites may **block title fetching** due to CORS.
- **Local storage is per browser** – Data won’t sync across devices.
- **No server/database** – Meant for **personal** use.

## Future Enhancements (Maybe 🤷‍♂️)
- ✅ Sync across devices using cloud storage.
- ✅ Custom notifications for CFP deadlines.
- ✅ Conference tagging/categorization.

## License
MIT – Use, modify, and share freely!

