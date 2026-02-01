# Barely Working Code - Website

Static website for [barelyworkingcode.com](https://www.barelyworkingcode.com)

## It works! Barely.

This is the marketing site for Barely Working Code and its products.

## Stack

- Static HTML/CSS
- No build process
- No JavaScript (because we respect your bandwidth)
- Hosted on Cloudflare Pages

## Local Development

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`

## Deployment

Deployed automatically to Cloudflare Pages when pushed to main.

Build settings:
- Build output directory: `/` (root)
- No build command needed

## Structure

```
web/
├── index.html          # Landing page
├── privacy.html        # Privacy policy
├── 404.html            # Error page
├── styles.css          # All styles
├── _headers            # Cloudflare headers config
├── _redirects          # URL redirects
└── assets/
    ├── favicon.svg     # Site icon
    └── og-image.svg    # Social sharing image
```

## License

Website content © 2025 Barely Working Code

---

*Status: Barely functional*
