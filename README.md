# GATE ECE 2027 Study Hub

A personal, local-only course organiser built with HTML, CSS and JavaScript. No backend, login, or paid service is required.

## Included
- Subject and topic checklist (editable)
- YouTube channel, playlist and lecture links
- Lecture status tracking
- Daily targets
- PYQ practice log
- Revision dates
- Mock-test scores
- Progress analytics
- JSON backup and restore
- Installable PWA and basic offline app shell

## Run on your computer
1. Extract the ZIP.
2. Open `index.html` in Chrome to try the basic app.
3. For PWA installation and offline caching, use a secure HTTPS host (GitHub Pages is free) or run a local web server.

## Publish free with GitHub Pages
1. Sign in at https://github.com/ and create a new **public** repository, for example `gate-ece-study-hub`.
2. Upload all files in this folder to the repository root. Ensure `index.html`, `app.js`, `styles.css`, `manifest.json`, `sw.js`, and `icon.svg` are at the root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the Pages deployment to finish. The site URL will look like `https://YOUR-USERNAME.github.io/gate-ece-study-hub/`.
7. Open that URL in Chrome. Use the browser's **Install** icon in the address bar or menu → **Install page as app**. On Android Chrome, use menu → **Add to Home screen** or **Install app**.

GitHub Pages serves public website files. Do not put private information in the repository. Your study data is stored in browser localStorage, not uploaded to GitHub.

## Data and backup
- Data stays in the browser profile where you use the app.
- Use **Backup & settings → Export backup** regularly. Store the JSON backup somewhere safe.
- Use **Import backup** to restore data in that browser.
- Clearing browser site data can delete your progress.
- Using the app on another device starts with a separate local dataset. Export/import a backup to transfer it.
- Browser local storage is not encrypted. Avoid storing passwords or sensitive personal information.

## Syllabus note
The included subject/topic checklist is a starter structure, not a guarantee of complete official coverage. GATE 2027 has revised syllabi. Check the official EC syllabus and update the topics to match it:
https://gate2027.iitm.ac.in/exam_papers_and_syllabus

## Troubleshooting
- If install options do not appear, make sure you opened the HTTPS GitHub Pages URL, not a local file URL.
- If the site is blank after updating, hard-refresh the page. If necessary, clear the site's cached data and reload.
- If you import a backup, it replaces the current local dataset; export first if you need both.
