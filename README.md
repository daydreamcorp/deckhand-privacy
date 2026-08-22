# deckhand-privacy

Public hosting for the privacy policy of Deckhand, a mobile app by Day Dream Corp.

This repo exists only because Google Play requires the privacy-policy link
submitted in Play Console to be an "active, publicly accessible... URL" — a
requirement the app's private source repository can't satisfy on its own.
The single page here is served via GitHub Pages at:

https://daydreamcorp.github.io/deckhand-privacy/

Source of truth for edits is `docs/privacy-policy.html` in the main
`deckhand` repository; this is a mirror, not authored independently.
Copy that file over `index.html` rather than editing here, or the two
drift — which is exactly what happened between 2026-08-12 and
2026-08-21, leaving a resolved TODO about the copyright holder live on
a public page for nine days.
