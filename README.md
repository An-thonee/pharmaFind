# PharmaFind Tailwind HTML Version

This folder is the converted Tailwind CSS + HTML version of the uploaded PharmaFind project.

## What changed
- Removed Bootstrap, jQuery folders, and old custom CSS files from the converted output.
- Rebuilt each page using Tailwind utility classes in the HTML.
- Kept the original images and linked them from `assets/images/`.
- Added responsive layouts for dashboard, pharmacy search, details, pharmacists, reminders, student hub, messages, notifications, profile, settings, login, and register pages.
- Kept `message.html` and `messages.html` so both old and new links work.

## How to open
Open `index.html` in your browser.

## How to host on GitHub Pages
1. Upload the contents of this folder to your repository.
2. Go to Repository Settings → Pages.
3. Choose your main branch and root folder.
4. Open the GitHub Pages link after it finishes deploying.

## Note
This version uses Tailwind through the CDN, so it works well for a simple static HTML project and GitHub Pages.
