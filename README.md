# Cockpit: iPhone car dashboard

A free landscape dashboard for the iPhone 15 Pro, styled after a BMW 440i interior:
black, red leather and orange instrument lighting.

## What's on it
- **Clock:** glowing orange 24-hour clock with the date, and red and orange livery stripes beside it.
- **Greeting:** "Good afternoon, Mustafa". You can change the name in Settings.
- **Live weather:** follows your location. Data comes from [Open-Meteo](https://open-meteo.com),
  which is free and needs no account.
- **Smart line:** one line under the weather shows the most useful thing right now:
  dusty air, rain in the next three hours, sunset within 90 minutes, or extreme heat.
- **Places:** الشقة and Work. One tap opens Google Maps with the route ready; tap **Start**.
- **Parked car:** tap to save where you parked; tap again for walking directions back.
  Holding the phone upright shows a "Your car" screen.
- **Favourites:** up to three people, shown as red leather circles. Tap one to choose **Call** or **WhatsApp**.
- **Apps:** Maps, Phone, WhatsApp, YT Music.
- **Trip timer and screen light:** the trip timer counts while you're in other apps (hold it to reset).
  An orange "Screen on" light means the screen will stay on.

## Install it so it opens like an app
Icons added from **Chrome** always open inside Chrome. Use **Safari**:
1. Open `https://mustafaas74.github.io/Cockpit/` in Safari.
2. Tap **Share**, then **Add to Home Screen**.
3. Keep **Open as Web App** switched on, then tap **Add**.
4. Delete any older Cockpit icon.

If Cockpit is ever opened inside a browser, it shows these steps once. They're also in Settings.

## First-time setup (once, while parked)
1. **Location:** allow it when your iPhone asks. Weather and parking use it.
2. **Places:** tap **الشقة**, then **Use my current location** while you're there, or type an address.
   Do the same for **Work**.
3. **Favourites:** tap **Add favourite** and enter a name and mobile number (05X XXX XXXX works).

To change a place or a favourite later, hold it for half a second.
Everything you enter is saved **only on your phone**, never in this public repository.

## Updates
Updates arrive the next time Cockpit opens with a connection. Swipe it away in the app switcher
and reopen it to update right away. The Home Screen icon picture only changes if you remove the
icon and add it again.

## Files
- `index.html`: the dashboard
- `manifest.webmanifest`, `sw.js`: make it installable and work offline (weather needs a connection)
- `splash/`: launch screens for the iPhone 15 Pro
- `icons/`: Home Screen icon
- `fonts/`: Oxanium (SIL Open Font License, see `fonts/OFL.txt`)
