# CAMPUS TRACE
CPUT lost and found for District Six, Bellville, Mowbray, Wellington and Granger Bay.

https://laverne816.github.io/campus_trace/

## Preview 
<img width="1417" height="751" alt="image" src="https://github.com/user-attachments/assets/4694437e-eeda-40f8-bedb-83f816f4b256" />

## Run locally
Open `index.html` in a browser, or serve this folder with a static web server.

## Notes
- Starter listings are illustrative examples, not current CPUT reports.
- Data is stored in browser `localStorage`; it is per-browser and is not secure or shared between users. Do not use this front end for real credentials or sensitive claim details.
- Student email placeholders use `@mycput.ac.za`; staff placeholders use `@cput.ac.za`.
- The map is a schematic location guide. Use the campus map link for real navigation.
- The AI assistant uses `window.claude` when hosted as a Claude artifact. Outside it, the chat reports that it is unavailable.
- Campus imagery is loaded from CPUT's public website; Google Fonts are loaded from the web. Both fall back gracefully when offline.

Files: `index.html`, `style.css`, `app.js`
