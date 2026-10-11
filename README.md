# Birthday Patro 🎂

A responsive birthday organizer with a cheerful dashboard, calendar, searchable birthday list, countdowns, and browser reminder support.

## Features

- Add, edit, search, filter, and delete birthdays
- Export birthday lists to CSV or full JSON backup
- Import JSON backups with merge or replace options and basic validation
- Dashboard stats for today, this month, and the next 30 days
- Countdown cards and a month calendar
- Per-person reminder lead time and default reminder setting
- Browser notifications when permission is granted and the app is open
- Local-first storage using browser localStorage
- Installable PWA shell with basic offline caching
- Responsive layout for desktop, tablet, and mobile

## Run it

This is a static site. Open `index.html` locally for basic use, or serve the folder over HTTP to enable the service worker and installable PWA features. GitHub Pages can host it without a build step.

## Important notification limitation

Browser notifications in this starter are checked when the site opens. The browser must grant notification permission, and reliable scheduled alerts while the site is fully closed require a push-notification backend/service. Email/SMS and cloud synchronization are not included yet.

## Data and privacy

Birthday data is saved in the current browser profile on the current device. Clearing browser site data can remove it. There is no account, server upload, or automatic cross-device sync in this starter.
