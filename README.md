# 2-Do-List

A calm, single-page to-do list for planning your day. Add tasks with due dates, track what you complete, and review recent activity in the history view. Tasks and activity are saved in your browser on the device you’re using.

## Features

- Add tasks up to 160 characters and schedule them for today or a future date
- Mark tasks complete or reopen them
- See how many tasks remain
- Review task activity from the last 7 days, including additions, completions, reopenings, and deletions
- Clear task history without deleting your current tasks
- Save tasks and history with browser `localStorage`
- Responsive layout, keyboard focus styles, and reduced-motion support
- No frameworks, build step, or external dependencies

## Run it

Open `index.html` in a modern web browser. The app runs entirely in the browser.

To publish it with GitHub Pages, add `index.html` and this `README.md` to a GitHub repository, then enable GitHub Pages in the repository settings.

## Data and privacy

Tasks and activity history are stored in this browser’s local storage. They are not sent to a server. They won’t automatically appear in another browser or on another device. Clearing the browser’s site data may erase them.

## Browser support

Use a modern browser with JavaScript, `localStorage`, and `crypto.randomUUID()` enabled.
