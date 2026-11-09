# WINTER ARC PWA

A personal, local-first Progressive Web App for daily habits, Brahmacharya/sadhana, meditation, walking, gym, vegetarian nutrition, weight check-ins and agency priorities.

## Included
- Editable daily habit and sadhana checklists: add custom habits and remove any listed habit; past check-ins remain saved\n- Daily habit and sadhana checklists with a consecutive-day activity streak
- Meditation timer with 5/10/20/30-minute presets
- Walking distance log against a gradual 5 km goal
- Gym session log
- Nutrition notes, calories, protein and water
- Weight check-ins
- Three daily agency priorities
- Daily motivational / reflective quotes
- Local persistence using browser storage
- Service worker cache for offline use after first successful load
- Installable PWA manifest and app icons

## Publish it
A PWA must be served from HTTPS (or localhost for testing) to install and use its service worker.

### Easiest: GitHub Pages
1. Create a GitHub repository named `winter-arc`.
2. Upload the contents of this folder to the repository root (not the zip itself).
3. In repository Settings → Pages, choose deploy from branch `main`, folder `/ (root)`.
4. Wait for GitHub Pages to publish the HTTPS site.
5. Open the published URL on your phone.

### iPhone
1. Open the published HTTPS URL in Safari.
2. Tap Share.
3. Choose Add to Home Screen.
4. Confirm Add. Launch WINTER ARC from the Home Screen.

### Android
1. Open the published HTTPS URL in Chrome.
2. Use the Install app prompt or menu → Install app / Add to Home screen.
3. Confirm installation.

## Privacy and storage
The app does not send your entries to a server. Progress is saved in the browser's local storage on that device. Clearing site data, uninstalling, or changing browsers/devices can remove or strand that data. Export/backup and cross-device sync are not included in this starter build.

## Personalisation notes
- Schedule includes a 3:30 AM wake-up and the preferred 10 PM bedtime as user-entered preferences. This is only 5.5 hours of sleep; most adults need 7–9 hours. The app flags this for reconsideration.
- 5 km is a target to build towards, not a requirement from day one.
- The 1,800 kcal and 100–120 g protein display are provisional planning references, not medical prescriptions.
- The app is a self-tracking tool, not medical advice.

## Development
No build step or external dependency is required. Serve this directory over localhost/HTTPS. The service worker will cache the app shell after the first visit.
