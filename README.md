# Chapter 6 Checkpoint - Ramon's Travel Blog

A five-page travel blog (Home, About, Destinations, Trip Planner, Contact) with a shared stylesheet and a mobile version.

## Structure
- Desktop pages in the root folder: `index.html`, `about.html`, `destinations.html`, `trip-planner.html`, `contact.html`
- `styles.css` - shared stylesheet
- `images/` - desktop images: `header-bg.jpg`, `paris.jpg`, `bali-1.jpg`, `bali-2.jpg`, `icons-sprite.jpg`
- `mobile/` - mobile version with its own stylesheet (`mobile/styles.css`) and `mobile/index.html`
- `mobile/images/` - mobile images: `header-bg-small.jpg`, `paris-small.jpg`, `bali-1-small.jpg`

## Notes
- The header icon uses `icons-sprite.jpg`, sized with the `.icon` rule in `styles.css`.
- The trip planner and contact forms have structure only and do not submit to a server yet.
- The mobile site is at `/mobile/` and links back to the full site.
