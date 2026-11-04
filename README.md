# LUMI Beauty

A responsive, English-language static makeup artist marketplace and beauty community, with makeup options for everyday wear, weddings, graduations, parties, photoshoots, cosplay, and creative effects. Built with HTML, CSS, and JavaScript.

## Preview

Open `index.html` in a browser. Each navigation item opens a separate page.

## Pages

- `index.html` — landing page
- `artists.html` and `profile.html?id=...` — artist search and profiles
- `learn.html`, `article.html?post=...`, `tutorials.html`, and `tutorial.html?layout=...` — journal and step-by-step makeup layouts
- `trends.html` — weekly social-style beauty feed
- `bookings.html` — booking requests saved in the current browser
- `color.html`, `join.html` — color studio and artist signup demo. The color quiz also recommends a seasonal makeup layout and tutorial.

## Publish on GitHub Pages

Upload the HTML pages, `styles.css`, `app.js`, `logo.svg`, and this README to a GitHub repository. Open **Settings → Pages**, select **Deploy from a branch**, choose your default branch and `/(root)`, then save.

## Demo limitations

The directory generates six illustrative sample artist profiles per province/city. Names, prices, reviews, service areas, and ward/commune options are not real listings. Booking requests are saved in the visitor's browser using local storage, so they are not delivered to an artist or shared across devices. Real booking delivery, artist responses, profile storage, and secure payments need a backend. Trend posts are also stored locally; the weekly editorial examples are sample content. No API key is included in browser code.

The location filter follows Vietnam's province/city → ward/commune/special zone structure. Districts are not a current selection level.

## Personal color studio

The color page includes a short seasonal self-reflection quiz, theory notes on undertone/value/chroma/contrast, and an optional local photo or camera draping preview. The quiz is educational inspiration, not a professional analysis; camera access generally requires HTTPS or localhost.

