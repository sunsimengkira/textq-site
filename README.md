# TextQ website

The TextQ marketing website is a small static site built with semantic HTML and modern CSS. It has no build step, runtime dependencies, analytics, forms, or external fonts.

## Local preview

From this directory, run:

```sh
python3 -m http.server 4173
```

Then open `http://localhost:4173/`.

## Structure

- `index.html` — Home
- `faq/` — FAQ
- `support/` — Support
- `privacy/` — Privacy Policy shell
- `assets/` — shared CSS and public images

The Privacy page contains a local-development placeholder and must receive final approved policy content before public deployment.
