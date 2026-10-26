# Cockpit: iPhone car dashboard

A free landscape dashboard for the iPhone 15 Pro, styled like a car's instrument cluster.

- **Gauge clock:** a 24-hour time readout. The amber scale lights up as the minutes of the hour pass,
  and it sweeps once at launch, like a cluster at ignition.
- **Places:** الشقة and Work. One tap opens Google Maps with the route ready; tap **Start**.
- **Shortcuts:** Maps, Phone, WhatsApp, YT Music.
- **Trip timer:** counts while you're in other apps. It starts fresh after 30 minutes away;
  hold it to reset.
- **Screen lamp:** the green sun symbol means the screen will stay on.

## Set up your places (once, while parked)
1. Tap **الشقة** (or **Work**). It shows *Tap to set* until it's saved.
2. Choose **Use my current location** while you're at the place, or type an address or place name.
3. Tap **Save place**. Its light turns amber.

To change a place later, hold it for half a second.

Your places are saved **only on your phone**. They are never written into this public repository.
iPhone asks for location permission only when you use *Use my current location*.

## While driving
- Tap a place, then tap **Start** in Google Maps.
- Come back to Cockpit by swiping right along the bottom edge of the screen,
  or by tapping the back link in the top-left corner.
- Google Maps keeps giving voice directions in the background. Newer versions also show
  the next turn in the Dynamic Island.

## Install or update
- Live at `https://mustafaas74.github.io/Cockpit/`
- First time: open it in Safari or Chrome, then Share → **Add to Home Screen**, and always launch
  it from that icon.
- Updates arrive automatically the next time Cockpit opens with a connection.

## Files
- `index.html`: the dashboard
- `manifest.webmanifest`, `sw.js`: make it installable and work offline
- `fonts/`: Barlow, a typeface based on highway signage (SIL Open Font License, see `fonts/OFL.txt`)
- `icons/`: Home Screen icon
