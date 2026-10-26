# Cockpit: iPhone car dashboard

A free landscape dashboard for the iPhone 15 Pro, styled like a modern car's curved display.

## What's on it
- **Greeting and clock:** "Good evening, Mustafa", a large 24-hour clock and the date.
- **Live weather:** follows your location. It shows temperature, conditions, and today's high and low.
  Data comes from [Open-Meteo](https://open-meteo.com), which is free and needs no account.
- **Smart line:** one line under the weather shows the most useful thing right now:
  dusty air, rain in the next three hours, sunset within 90 minutes, or extreme heat.
- **Places:** الشقة and Work. One tap opens Google Maps with the route ready; tap **Start**.
- **Parked car:** tap to save where you parked. Later, tap again (or hold your phone upright)
  for walking directions back.
- **Favourites:** up to three people. Tap one to choose **Call** or **WhatsApp**.
- **Apps:** Maps, Phone, WhatsApp, YT Music.
- **Trip timer and screen light:** the trip timer counts while you're in other apps (hold it to reset).
  A blue light means the screen will stay on.

## First-time setup (once, while parked)
1. **Location:** allow it when your iPhone asks. Weather and parking use it.
2. **Places:** tap **الشقة**, then **Use my current location** while you're there, or type an address.
   Do the same for **Work**.
3. **Favourites:** tap **Add favourite** and enter a name and mobile number (05X XXX XXXX works).
4. **Settings** (gear icon): change the name used in the greeting.

To change a place or a favourite later, hold it for half a second.
Everything you enter is saved **only on your phone**, never in this public repository.

## Install or update
- Live at `https://mustafaas74.github.io/Cockpit/`
- First time: open the link in Safari or Chrome, then Share → **Add to Home Screen**, and always
  launch it from that icon.
- Updates arrive the next time Cockpit opens with a connection. Swipe it away in the app switcher
  and reopen it to update right away.

## Files
- `index.html`: the dashboard
- `manifest.webmanifest`, `sw.js`: make it installable and work offline (weather needs a connection)
- `fonts/`: Saira (SIL Open Font License, see `fonts/OFL.txt`)
- `icons/`: Home Screen icon
