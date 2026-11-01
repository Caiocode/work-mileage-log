# Work Mileage Log

A small web app for logging work days and the kilometres driven between places: start time, break, end time, total hours, and the route of the day (for example Home → Place A → Place B → Home). At the bottom of each month it shows total hours, total kilometres and kilometres × your rate per km (0,30 € by default).

Available in English, German and Polish.

## Use it

Open the app in your browser: **https://caiocode.github.io/work-mileage-log/**

### Install it like an app

- **iPhone / iPad:** open the link in Safari → Share button → *Add to Home Screen*.
- **Android:** open the link in Chrome → ⋮ menu → *Add to Home screen* (or *Install app*).
- **Windows / Mac (Chrome or Edge):** open the link → browser menu → *Install page as app* / *Install this site as an app*.
- **Mac (Safari):** File → *Add to Dock*.

The app also works without an internet connection once it has been opened.

## Where your data is kept

Everything you enter stays **on your own device**, in your browser. Nothing is sent to a server and nobody else can see it.

- Each phone or computer keeps its own log. They do not sync with each other.
- Use **Export backup** to save a backup file, and **Import backup** to load it on another device or after clearing your browser data.
- Clearing the browser's site data deletes the log on that device, so export a backup from time to time.

## How it works

- **Places:** your home, plus two lists: Ferienwohnungen and private clients.
- **Distances:** enter each distance between two places once (the *Check in Maps* link opens Google Maps with both addresses). It counts in both directions and is reused for every trip.
- **Logbook:** log a day with its times and route; kilometres are added up from the saved distances. *Copy for Excel* and *Download CSV* export the month.

Built as a single `index.html` with no build step. `sw.js` provides offline support and `manifest.webmanifest` makes it installable.
