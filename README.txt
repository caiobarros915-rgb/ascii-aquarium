ASCII AQUARIUM - install on your phone
======================================

This folder is a complete installable web app (a "PWA"):
  index.html            the app
  manifest.webmanifest  name, colours and icons for the home screen
  sw.js                 lets it open offline
  icon-*.png, apple-touch-icon.png   app icons

STEP 1 - Put the folder online (free, pick one)
-----------------------------------------------
Phones only install web apps from a secure (https) address, so the folder
has to be hosted somewhere. Unzip it first, then:

 A) Netlify Drop (easiest, no account needed to try it)
    Open app.netlify.com/drop, drag the unzipped folder onto the page.
    You get an https address straight away. Create a free account to keep it.

 B) Cloudflare Pages -> "Upload your static files" and upload the folder.

 C) GitHub Pages: create a repository, upload these files, then
    Settings -> Pages -> deploy from the main branch.

Keep the address private if you like: it is just a link, and your progress
is saved on your phone, not on the server.

STEP 2 - Install it
-------------------
 iPhone (use Safari):  open the address, tap the Share button,
                       choose "Add to Home Screen", then Add.
 Android (use Chrome): open the address, tap the menu (three dots),
                       choose "Install app" or "Add to Home screen".

Open it from the new icon: it runs full screen and works offline.

GOOD TO KNOW
------------
 * Progress is stored on that phone only. It does NOT sync between devices.
 * On iPhone, the home-screen app has its own storage, separate from Safari.
   If you played in Safari first, use Backup & Settings -> "Create backup
   code" there, then paste it into the installed app under "Restore".
 * Make a backup code now and then. Clearing the browser's site data, or
   deleting the app, erases progress.
 * To update the app later, upload the new files to the same place. The
   installed app picks up changes the next time it opens while online.
