# Bio Website (Static — Vercel Ready)
**Storage:** settings are in the browser's LocalStorage; uploaded media (logo, video, music, images) are in IndexedDB. This is NOT cloud storage — data lives only in the browser used for editing. Use Backup → Export to save settings (media files are not included in the export).
## Run
Open `index.html` via any static server (e.g. `npx serve`) or deploy.
## Deploy to Vercel
1. Upload this folder to GitHub. 2. Vercel → New Project → import repo. 3. Framework: Other, no build command. 4. Deploy.
## Admin
Click the profile logo → enter password (default `789789`) → Done. Change it in Security. The password is stored hashed (SHA-256) but this is client-side protection only and is not secure against a determined visitor; move to a backend for real security.
## Media / Theme / Backup
Upload in Admin → Videos / Music / Gallery / Profile. Theme colors (HEX + picker) apply live. Backup → Export/Import/Reset.
