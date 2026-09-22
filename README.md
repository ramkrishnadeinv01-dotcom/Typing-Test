# Typing Test — GitHub Pages

A client-side typing assessment that can be hosted directly on GitHub Pages.

## Features
- 10-minute timer
- Candidate name and employee/roll number
- Copy/paste/cut disabled
- Drag-and-drop disabled
- Context menu disabled during test
- Full-screen request
- Tab/window visibility changes counted
- Gross WPM, Net WPM, accuracy and errors
- Print / Save as PDF result
- Mobile-responsive layout

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` and `/ (root)`, then **Save**.
6. GitHub will provide a public URL.

## Important
This is a browser-side assessment. It discourages normal copy/paste and records common tab-switch events, but no ordinary website can guarantee that a candidate cannot use another device, OCR, accessibility tools, developer tools, or other external assistance.

To change the test duration or passage, edit the `DURATION` and `PASSAGE` constants near the bottom of `index.html`.
