REFLEX — Personal Cyberdeck Prototype 0.1

WHAT THIS IS
A responsive web app prototype designed to test on a Samsung Galaxy Z Fold.
It includes:
- Home dashboard
- Journal entries
- Personal catalogue (board games, books, hobbies)
- Basic local recommendation matching
- Daily task list
- Project/idea notes
- JSON data export

IMPORTANT LIMITATIONS
- This is a prototype, not a finished AI assistant.
- The recommendation engine uses simple local matching rules; it does not call an AI model.
- Data is stored in the browser's local storage on the device/browser where you use it.
- There is no account, cloud sync, or encryption yet. Do not store sensitive journal entries.
- The PWA offline/install features require hosting over HTTPS (or localhost).

HOW TO TEST ON YOUR SAMSUNG FOLD
1. Unzip this folder.
2. Host the contents on an HTTPS static host, for example GitHub Pages or Netlify.
   Upload index.html, manifest.webmanifest, sw.js and icon.svg to the site root.
3. Open the resulting HTTPS URL in Chrome or Samsung Internet on your Fold.
4. Open the browser menu and choose "Add to Home screen" or "Install app" if offered.
5. Try both the cover screen and unfolded screen. The layout is responsive.
6. Add a few board games/books under Collections, then try Decision Engine.

QUICK LOCAL TEST
You can open index.html on a computer to preview the interface, but PWA installation and
service-worker offline support will not work from a file:// URL.

NEXT DEVELOPMENT STEPS
- Import the real board game and book catalogue.
- Improve player-count, playtime, mood and complexity matching.
- Add conversational AI through an optional secure backend.
- Add journal categories, search, edit and export/import.
- Add encrypted backups and optional sync before using it for private journalling.
