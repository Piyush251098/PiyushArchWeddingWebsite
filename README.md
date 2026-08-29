# Archana & Piyush Wedding Website

A static wedding invitation website with RSVP form connected to a Google Apps Script backend that stores submissions in a Google Sheet.

## Folder structure

- index.html
- hero-image.png
- story-1.webp
- story-2.webp
- story-3.webp
- culture-archana.webp
- culture-piyush.webp
- backend/
  - Code.gs

## How to use

1. Open the Google Sheet you want to store RSVPs in.
2. Go to Extensions → Apps Script.
3. Paste the contents of `backend/Code.gs` into the project.
4. Deploy as a Web App:
   - Execute as: Me
   - Who has access: Anyone
5. Copy the Web App URL.
6. In `index.html`, replace the placeholder:
   `const SHEET_WEB_APP_URL = 'PASTE_YOUR_GOOGLE_APPS_SCRIPT_WEB_APP_URL_HERE';`
   with your real URL.
7. Upload everything to a GitHub repository.
8. Enable GitHub Pages for the repo.

## Notes

- The frontend is static HTML/CSS/JS.
- The backend is a Google Apps Script endpoint that appends rows to the sheet.
- It is free and simple for a personal wedding site.
