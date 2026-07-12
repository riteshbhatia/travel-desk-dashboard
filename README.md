# Travel Desk — encrypted dashboard

A single static, **client-side-encrypted** page (staticrypt / AES-256 + PBKDF2).
The trip data is not present in the page source — it decrypts in the browser only
after the correct passphrase is entered. Safe to host publicly; the plaintext
itinerary is never exposed without the passphrase.

Served via GitHub Pages. Rebuilt from the private `travel_desk` repo's read-only
`tracker.html`.
