# Macantsaoir Capital Partners Website

Premium static website package for GitHub Pages.

## Files

- `index.html` - main webpage
- `styles.css` - full responsive styling
- `script.js` - mobile menu and scroll reveal effects
- `assets/mcp-logo-capital-partners.svg` - recreated gold logo with Capital Partners wording
- `assets/london-hero.svg` - dark London-style hero artwork
- `assets/favicon.svg` - browser tab icon
- `assets/MCP_Logo.png` - original uploaded logo reference, if included

## GitHub Upload Instructions

1. Create a new repository on GitHub called `macantsaoir-capital-partners`.
2. Upload all files and folders from this package.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`.
6. Save.
7. Your site will publish at your GitHub Pages URL.

## Contact Form

The contact form is visually complete but not connected yet. To make it send enquiries, replace the blank form action in `index.html`:

```html
<form class="contact-form reveal" action="" method="POST">
```

with a Formspree, Netlify Forms, or Power Automate HTTP endpoint.

## Custom Domain

After buying a domain such as `macantsaoircapital.com`, add it under **Settings > Pages > Custom domain** in GitHub.
