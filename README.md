# Startup Growth Magazine — Homepage Redesign

A redesigned homepage for [startupgrowth.ca](https://startupgrowth.ca/): Canada's magazine for founders, startups and scaleups.

## Preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## What's in it

- **Single file:** HTML, CSS and a little vanilla JS, with no build step. Fonts load from Google Fonts (Newsreader + Instrument Sans).
- **Sections:** utility bar, masthead, sticky nav, headline ticker, lead story with Most Read, Business Awards band, Startups & Technology, Founder Interviews, Investment & Capital / Funding Desk, AI, Share Your Story, Latest News + newsletter, footer.
- **Theming:** colours are CSS variables on `:root`; light and dark mode (system preference plus a toggle).
- **Responsive:** tested at 375px and 1366px; mobile gets a slide-down menu.
- **Accessibility:** skip link, visible focus, labelled icon buttons, 44px tap targets, reduced-motion support.

## Still to do

- Replace the patterned image placeholders (`.media` blocks) with real article photography.
- Wire links and the newsletter form to the live site / mailing provider.
- Port into the site's CMS theme (e.g. WordPress templates).
