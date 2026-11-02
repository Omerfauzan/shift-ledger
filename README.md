# Shift Ledger

A small app I made to track my casual shifts. I add my start and finish times and any unpaid break, and it shows my hours for the week and what I'll get paid.

## What it does
- Log shifts with date, start, finish and unpaid break
- Handles overnight shifts
- Weekly hours, days worked and estimated pay (before tax)
- Tag shifts by location (main shop or other)
- Change the hourly rate, and old shifts keep the rate they were saved with
- Works offline and can be added to the home screen like an app
- Backup and restore so I don't lose my shifts

## Where my data goes
Everything is saved on the phone in the browser's local storage. Nothing is sent to a server. If you clear site data or delete the app, the shifts are gone, so use Backup and restore now and then.

## Install on iPhone
1. Open the site in Safari
2. Tap Share, then Add to Home Screen

## Files
- `index.html` is the whole app
- `sw.js` lets it work offline
- `manifest.webmanifest` and the icons make it installable
