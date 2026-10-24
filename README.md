# Reading Companion

A mobile-friendly reading journal and tracker. It saves books, reading notes, daily goals, assignments, and reflections in the browser on your device.

## Files
- `index.html` — the app
- `manifest.webmanifest` — installable app settings
- `sw.js` — offline caching
- `icon.svg` — app icon

## Publish with GitHub Pages
1. Create a **public** GitHub repository named `reading-companion`.
2. Upload all four app files plus this README to the repository root (not inside another folder).
3. Open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for GitHub to publish. Your URL will look like `https://YOUR-USERNAME.github.io/reading-companion/`.
6. Open the URL in Chrome on your Android phone. Use the three-dot menu → **Add to Home screen** or **Install app** if shown.

## Important data and reminder limits
- Data is stored locally in this browser on this device. It is not automatically synced across phones. Use **Settings & backup → Download backup** regularly.
- Notifications are best-effort while the app is open. Browsers may suspend the app when it is closed, and this app has no server to send scheduled push notifications. For a dependable alarm when the app is closed, set a repeating alarm in your phone's Clock app too.
- GitHub Pages requires HTTPS for service workers and install features; the published GitHub Pages URL provides HTTPS.
