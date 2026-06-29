HOUSE MISTRAL — Static website (by Pagolander)
================================================

CONTENT
  index.html      → the whole website (HTML/CSS/JS, no build step, no dependencies)
  images/         → 18 photos used by the site
  sitemap.xml     → for Google indexing
  robots.txt      → for Google crawling

HOW TO PREVIEW LOCALLY
  Double-click index.html — it opens and works in any browser.
  (Note: the Google Map needs internet to load; everything else works offline.)

HOW TO UPDATE THE LIVE URL (if you switch to a custom domain)
  Open index.html and update the domain in 4 places (all in the <head>):
    canonical href, og:url, og:image, twitter:image
  Also update the <loc> in sitemap.xml and the Sitemap: line in robots.txt.
  Current domain: https://house-mistral.vercel.app

NOTES
  - Booking via WhatsApp: +30 694 477 1000 / housemistral@gmail.com
  - Languages: English + Greek (toggle in the top-right).
  - Reviews link to Booking.com — no form or backend needed.
  - To update content (rooms, photos, text): contact Pagolander.
