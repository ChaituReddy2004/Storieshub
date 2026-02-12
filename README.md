# Storieshub

A lightweight static front-end for the Stories hub Publishing site — a small collection
of HTML pages, CSS, and a little JavaScript that demonstrates the site's main flows
for authors: publishing, account creation, community, and help resources.

## Quick start

- Open the site in your browser by double-clicking [index.html](index.html).
- Or serve locally with Python 3:

```bash
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

## What you'll find

- **Pages:** Several ready-made pages for common flows: [index.html](index.html), [create_account.html](create_account.html), [content_upload.html](content_upload.html), [ebook_details.html](ebook_details.html), [ebook_pricing.html](ebook_pricing.html), [author_profile.html](author_profile.html), [bookshelf.html](bookshelf.html), [community_forum.html](community_forum.html), [forum_topic.html](forum_topic.html), [help_center.html](help_center.html), [marketing.html](marketing.html), [reports.html](reports.html), [signin.html](signin.html), [signin_password.html](signin_password.html).
- **Create flows:** Templates for creating hardcover/paperback/ebook: [create_hardcover.html](create_hardcover.html), [create_paperback.html](create_paperback.html), [create_selection.html](create_selection.html).
- **Static assets:** Images under `assets/images/` and site styles in `style.css` plus extra CSS in the `css/` folder.
- **JS:** Basic client-side code including localization support in [js/i18n.js](js/i18n.js).

## Project structure

- `index.html` — Home/marketing landing page.
- `style.css` — Primary stylesheet for shared layout and components.
- `css/` — Additional CSS files (for alignment and create-book specific styling).
- `assets/images/` — Logos and illustration assets.
- `js/` — Small JavaScript helpers; see [js/i18n.js](js/i18n.js) for localization.
- `*.html` — Multiple page templates for flows and pages used by the site.

## Localization

This project includes a simple i18n helper: [js/i18n.js](js/i18n.js). Use it to
provide client-side translated strings or to wire up language-selection UI.

## Documentation & notes

- Functional and alignment notes are present in the repository: [FUNCTIONALITY_COMPLETE.md](FUNCTIONALITY_COMPLETE.md), [LANGUAGE_AND_FUNCTIONALITY.md](LANGUAGE_AND_FUNCTIONALITY.md), [PERFECT_ALIGNMENT_GUIDE.md](PERFECT_ALIGNMENT_GUIDE.md).

## Contributing

This is a static prototype. To improve it:

- Update or add pages and styles in the project root.
- Add images to `assets/images/` and reference them from the HTML.
- If you need a local dev server with live reload, use a tool like `live-server` or an npm-based static server.

## License

No license file is included. Add a `LICENSE` if you intend to publish or share.

---

If you want, I can also:

- add a short development `Makefile` / `package.json` with a `start` script;
- expand the README with screenshots and a contributor guide.

—

Generated from the workspace files and page templates.