# McKenzie Customs

Website for McKenzie Customs — custom laser engraving and 3D printing, based in Spartanburg, South Carolina.

Plain HTML/CSS/JS, no build step required. Pages: `index.html`, `gallery.html`, `services.html`, `about.html`, `contact.html`.

## Preview locally

Open `index.html` directly in a browser, or run a quick local server from this folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Replace the placeholder content

- **Logo**: swap `images/logo.svg` for your real logo (drop in a file and update the `src="images/logo.svg"` references in each page's `<header>` and `<footer>`).
- **Photos**: each placeholder graphic in `images/` (`hero.svg`, `about.svg`, `gallery-1.svg` through `gallery-8.svg`) has a matching `<img src="...">` in the HTML — replace the file and update the `src`/`alt` text with real photos of your work.
- **Contact info**: update the phone, email, and address in `contact.html` (and the footer on every page).
- **Contact form**: the form on `contact.html` posts to Formspree. Sign up free at [formspree.io](https://formspree.io), create a form, and replace the `action="https://formspree.io/f/your-form-id"` URL with your own.
- **Map**: the embedded map on `contact.html` currently points to "Spartanburg, SC" generally — update the `src` query in the `<iframe>` with your exact address once you have a shop location to show.
- **Social links**: the Facebook/Instagram/Etsy icons in `contact.html` link to `#` — update `href` with your real profile URLs.

## Deploy to GitHub Pages

1. Push this repo to GitHub (if not already).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — your site will be live at `https://<username>.github.io/<repo-name>/` within a minute or two.
