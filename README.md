# Om Japa Tracker — Version 100

Minimalist, mobile-first PWA source package.

## Default sankalpa
- Start: 11 October 2026; 82 days through 31 December 2026
- 34 malas/day × 108 chants/mala = 3,672 chants/day
- Total: 2,788 malas = 301,104 chants
- At 2 seconds per chant: 2h 2m 24s/day excluding breaks

## Features
Daily tap-to-complete mala grid; undo; all-day calendar; overall progress; current/best streaks; weekly analytics and milestones; editable plan; theme and grid size controls; optional haptics/confirmation; local save; JSON backup export/import; print report; custom icons; service worker and offline cache after first successful online load.

## Install on iPhone
This is a PWA source package, not an installed app or signed .ipa. It must be hosted over HTTPS for Home Screen installation.
1. Extract this ZIP on your Mac and upload the files in this folder to a GitHub repository.
2. Repository Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
3. Open the resulting HTTPS URL in Safari on iPhone.
4. Share → Add to Home Screen → Add. Open once online for offline caching.

Local testing: run `python3 -m http.server 8000` in this folder and open `http://localhost:8000` on your Mac.

## Data limitations
Progress stays in this browser profile and is not sent to a server. There is no automatic iCloud sync. Export backups regularly; clearing browser/site data may erase progress. Test on the target iPhone before relying on the app for the entire sankalpa.
