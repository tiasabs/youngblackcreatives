# Young Black Creatives — Render static site

A multi-page static website. It has no WordPress dependency, build step, server, or database. Render publishes only `render-site/`.

## Pages

- `render-site/index.html` — home
- `render-site/about-us.html`
- `render-site/activities.html` — includes the photo gallery
- `render-site/community-approach.html`
- `render-site/our-partners.html`
- `render-site/support-us.html`

## Deploy on Render

1. Push this project to the GitHub repository connected to Render.
2. In Render, use **New → Blueprint** and connect the repository. `render.yaml` configures the static site, with `render-site/` as its publish directory and no build command.
3. If creating the site from **New → Static Site**, leave Root Directory and Build Command empty, and set Publish Directory to `render-site`.

## Before sharing publicly

- Add the programme’s preferred contact details on `support-us.html`.
- The programme has permission for the supplied photographs, as confirmed by the user.
- Verify partner descriptions and the place-name spelling in public copy before launch.

Edit the HTML files and `site.css` in `render-site/`. Site-wide colors and navigation are shared across pages.
