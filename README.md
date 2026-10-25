# Cockpit — iPhone car dashboard

A free landscape dashboard for the iPhone 15 Pro: 24-hour clock, date, trip timer,
and big shortcuts to Google Maps, Phone, WhatsApp and YouTube Music.

## Files
- `index.html` — the dashboard
- `manifest.webmanifest`, `sw.js` — make it installable and work offline
- `icons/` — Home Screen icon

## 1. Put it online (free, GitHub Pages)
1. Create a free account at github.com.
2. Tap **+ → New repository**, name it `cockpit`, set it to **Public**, create it.
3. Tap **Add file → Upload files** and upload everything in this folder
   (keep the `icons` folder as a folder). Commit.
4. Go to **Settings → Pages**. Under *Branch*, choose `main` and `/ (root)`, then Save.
5. After a minute, your dashboard is at `https://YOUR-USERNAME.github.io/cockpit/`.

## 2. Install on the iPhone
1. Open that link in **Safari**.
2. Tap **Share → Add to Home Screen → Add**.
3. Always open Cockpit from the Home Screen icon (not from Safari).

## 3. First-drive checks
- **Screen stays on:** the dot next to the trip timer is green ("Screen on").
  If it shows orange "Tap to keep screen on", tap anywhere. If it never turns green,
  iOS isn't allowing wake lock for Home Screen apps on your version.
- **Phone tile:** uses an undocumented link. If it does nothing, tell Claude and
  it can be switched to call a favourite contact instead.
- **Returning from Maps:** use the "◀ Cockpit" link at the top-left of the screen,
  or the App Switcher.

## Trip timer
- Starts when you open Cockpit; keeps counting while you're in Maps.
- Starts fresh if Cockpit hasn't been open for 30 minutes.
- Long-press the timer to reset it manually.

## Recommended iPhone settings (no app needed)
- **Driving Focus** (Settings → Focus → Driving): allow only the people and apps you
  want, so only those banners appear over the dashboard.
- **Announce Notifications** (Settings → Notifications) to hear messages via the car speakers.

## Updating
Edit or re-upload `index.html` on GitHub. The phone picks up the new version the next
time it opens Cockpit with a connection.
