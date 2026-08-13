# Grid Prix — F1 Mind Games

An unofficial, fan-made puzzle game (Sudoku, Word Hunt, Crossword) with an F1-inspired theme. Not affiliated with F1, FIA, or any team.

## Play online

Visit the live site (GitHub Pages). Progress, achievements, and settings are saved locally in your browser, so nothing is lost between visits.

## Play offline

The game works fully offline — puzzles, progress, achievements, and profile all run locally. Only the global leaderboard needs a connection (score submissions queue automatically and sync once you're back online).

**Option 1: Install it as an app (recommended for regular play)**

1. Visit the live site once while online.
2. Install it:
   - **Chrome/Edge (desktop):** click the install icon in the address bar, or menu → "Install Grid Prix".
   - **Android Chrome:** menu → "Add to Home screen" / "Install app".
   - **iOS Safari:** Share button → "Add to Home Screen".
3. Launch it from your home screen/app list any time — no browser or connection needed.

This works because the site registers a service worker on first visit that caches everything it needs, so future loads run entirely from your device.

**Option 2: Just keep the browser tab/bookmark**

After visiting the site once while online, you can reopen the same tab or bookmark later without a connection — the service worker serves it from cache automatically.

**Option 3: Run the file directly**

Download `index.html` (and the `avatars/` folder) from this repo and open `index.html` directly in a browser (double-click, or File → Open). No install or server required — this always works offline since it doesn't depend on the service worker at all.
