VANAKESH HERBAL OIL — FULL WEBSITE
==================================

Files
-----
index.html    The complete website (design, photos, videos and scripts are all inside this one file)
vercel.json   Settings used when hosting on Vercel

Open it
-------
Double-click index.html to open the website in your browser.

Changes in this version
-----------------------
- Payment: the UPI QR code now pays to 9008324225@fam (amount filled in automatically).
  The UPI ID and an "Open in UPI app" link are shown under the QR.
- "From the mirror" (Reviews) now comes before Instagram, on the page and in the menu.
- The Vanakesh logo (intro and top bar) is now written on one line, with no gap between the letters.
- The floating "Upload photos" button has been removed. Everything else looks the same.
- Your saved photos still load (they are kept in the browser).
- The photo panel is still reachable: add #photos to the end of the page address,
  or press Ctrl+Shift+P on a computer.
- "Download page with my photos" now saves the 12 card photos AND the reel videos
  inside the file. It will not download an empty file: if no photos are saved in the
  browser, it tells you instead.

To put your own photos in permanently
-------------------------------------
Send the photos to Claude with the card each one belongs to, and they can be
built straight into index.html so they show everywhere and in every download.

Host it online
--------------
Option A (Vercel):  put these files in a folder, then run:
    npx vercel --prod
Option B (any hosting): upload index.html to your hosting (Netlify, cPanel, GitHub Pages, etc.)
