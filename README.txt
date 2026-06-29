HOUSE MISTRAL — Static website (by Pagolander)
================================================

CONTENT
  index.html      → the whole website (HTML/CSS/JS, no build step, no dependencies)
  images/         → 18 photos used by the site

HOW TO PREVIEW LOCALLY
  Double-click index.html — it opens and works in any browser.
  (Note: the Google Map needs internet to load; everything else works offline.)

HOW TO PUT IT LIVE
  Option A — Vercel (recommended)
    1. Go to vercel.com → New Project → drag this whole folder (house-mistral-site).
    2. Framework preset: "Other" / static. No build command needed.
    3. Deploy. You get a live URL (e.g. house-mistral.vercel.app).

  Option B — Netlify
    1. Go to app.netlify.com/drop
    2. Drag this whole folder onto the page. Done — you get a live URL.

AFTER YOU HAVE THE LIVE URL (important for sharing previews)
  Open index.html and replace every "REPLACE-WITH-YOUR-DOMAIN" with your real
  domain (e.g. house-mistral.vercel.app). There are 4 of them, all in the <head>.
  This makes the title + photo show correctly when the link is shared on
  WhatsApp / Facebook. The site works even without this — it only affects share previews.

NOTES
  - Booking via WhatsApp: +30 694 477 1000 / housemistral@gmail.com
  - Languages: English + Greek (toggle in the top-right).
  - Guest reviews submitted via the form are stored only in that visitor's browser
    (demo). For real shared reviews, that becomes a v2 feature (backend/CMS).
  - The "See all reviews on Booking.com" link can be removed or its exact URL
    updated in index.html if you prefer.
