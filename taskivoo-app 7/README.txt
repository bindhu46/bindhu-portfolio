TASKIVOO — Install as a phone app
==================================

This folder is a small self-contained "app": index.html, manifest.json,
sw.js (offline support), and an icons/ folder. To get a real home-screen
icon that opens full-screen (no browser address bar), the files need to
be reachable at a web address — phones won't install a proper PWA icon
from a file sitting in Downloads.

EASIEST OPTION — Netlify Drop (free, no account, ~1 minute)
1. On your computer, go to https://app.netlify.com/drop
2. Drag the whole "taskivoo-app" folder onto the page
3. It gives you a live link like https://random-name-123.netlify.app
4. Open that link on your phone (Safari on iPhone, Chrome on Android)
5. iPhone: tap the Share icon → "Add to Home Screen"
   Android (Chrome): tap the ⋮ menu → "Add to Home screen" / "Install app"
6. You now have a Taskivoo icon that opens full-screen, works offline,
   and keeps your saved applications.

ALSO WORKS — GitHub Pages
If you already use GitHub: create a repo, upload these files, turn on
GitHub Pages in Settings, then open the resulting github.io link on your
phone and add it to your home screen the same way.

QUICK-AND-DIRTY OPTION — no hosting at all
Email or AirDrop just index.html to your phone and open it in Safari,
then "Add to Home Screen." This gives you an icon that launches the app,
but skips the offline support and full-screen mode that come from proper
hosting — you'll see Safari's address bar.

Note: your saved job applications live in the browser you open the app
in, on that device. Installing it as an app on your phone starts a
separate, empty board from the one on your laptop — they don't sync
automatically.
