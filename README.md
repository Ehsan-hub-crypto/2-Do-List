# 2-Do-List

A calm, single-page to-do list for planning your day. Create a local account, add tasks with due dates, track completions, and review recent activity.

## Features

- Create an account and sign in with a username and password
- Add tasks of up to 160 characters and schedule them for today or a future date
- Mark tasks complete or reopen them
- See how many tasks remain
- Review additions, completions, reopenings, and deletions from the last 7 days
- Clear activity history without deleting current tasks
- Get a celebration when you finish the tasks due today
- Responsive layout, keyboard focus styles, and reduced-motion support
- Runs as a standalone HTML file with no frameworks or build step

## Run it

Open `index.html` in a modern browser. For account creation and encrypted storage, use a secure context such as HTTPS. GitHub Pages provides HTTPS when the site is published.

## Accounts and data

This is a static, browser-only app. It does not use a server, and accounts do not sync across browsers or devices. Account information and encrypted task data are stored in the browser's local storage. The app encrypts task data with a key derived from your password, but this is not a hosted account or cloud backup.

Passwords cannot be reset. Keep your password safe. Clearing this site's browser data can remove accounts and saved lists permanently.

## Browser support

Use a modern browser with JavaScript, `localStorage`, Web Crypto, and `crypto.randomUUID()` enabled.
