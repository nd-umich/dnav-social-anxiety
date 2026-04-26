# DNA-V Behavioural Log

A self-monitoring web app for tracking behavioural experiments using the DNA-V model (Discoverer, Noticer, Advisor, Values).

## What's in the box

A single `index.html` file. That's it. No build step, no dependencies, no server-side anything. Open it in any modern browser and it works.

## Hosting it

Three easy options:

**GitHub Pages** — drop `index.html` into a repo, enable Pages on the main branch, you get a free `https://yourusername.github.io/repo-name/` URL.

**Netlify or Vercel** — drag the file (or folder) onto netlify.com/drop or use the Vercel CLI. Free tier is plenty.

**Local file** — just double-click `index.html`. Works on a phone too: email the file to yourself, open it in your browser, and add it to your home screen.

## Mobile use

The app is mobile-first. On iOS or Android, after opening the URL in your browser, use "Add to Home Screen" (Safari: share button → Add to Home Screen; Chrome: menu → Add to Home screen) to get an app-like icon. After that it opens full-screen with no browser chrome.

## Data and privacy

Entries are stored in `localStorage` on the device only. They never leave the user's phone unless they hit "Export." The export produces a JSON file the user can save to iCloud, Google Drive, email to themselves, etc., and re-import on another device.

There is no analytics, no tracking, no network requests after the initial page load. The only external request is to Google Fonts for typography (Fraunces and IBM Plex Sans). If you want to remove even that, download the font files, host them yourself, and replace the `<link>` in the `<head>`.

## Customising the tools

Open `index.html` in any text editor and look for the `ADVISOR_TOOLS`, `NOTICER_TOOLS`, `VALUES_LIST`, and `EMOTIONS` arrays near the top of the `<script>` block. Each has a clear structure — add, remove, or edit entries directly. No build step needed; just save and refresh.

## Disclaimer

This is a self-monitoring tool, not a substitute for professional mental health care. Users in distress should reach out to a qualified clinician.
