READ BETWEEN THE LINES — Case File 017
KATHA – The Book Club | KMEC

HOW TO PREVIEW
1. Keep index.html in this folder.
2. Double-click index.html to open it in a modern browser.
3. For deployment, upload index.html to any static hosting provider (GitHub Pages, Netlify, Vercel, etc.). No build step is required.

ORGANISER SETTINGS
Open index.html and find the script near the bottom labelled:
  ORGANISER SETTINGS — replace placeholders here before publishing.

Update these values in EVENT_CONFIG:
- registrationUrl: paste the official Google Form URL (must begin with https://)
- registrationSheetUrl: organiser-only spreadsheet URL. It is deliberately not exposed as a public link.
- deadline: enter the confirmed deadline; do not publish a placeholder if unknown.
- contact: enter the approved contact details.
- contactUrl: optional mailto: address or official contact URL.
- instagramUrl: paste the official KATHA Instagram URL (must begin with https://)
- venueNote: replace with the confirmed starting point or leave the announcement text.

The registration buttons do not pretend to submit a form. Until registrationUrl is configured, they show a small “coming soon” note. Once a valid HTTPS form URL is added, they open it in a new tab.

NOTES
- The story is fictional; the public site does not reveal a culprit, clue locations, or solution.
- Responsive layout, mobile navigation, FAQ accordion, smooth in-page navigation, reduced-motion support, page metadata, and a custom inline SVG favicon are included.
- Google Fonts are loaded remotely; if unavailable, serif/system fallback fonts are used.
