# TrailFreaks Landing Page

Static site. Open `index.html` directly, or host anywhere that serves static files
(GitHub Pages, Netlify, Vercel, Cloudflare Pages, S3).

## GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder (or push via git).
3. In repo Settings → Pages, set source to the `main` branch, root folder.
4. Your site will be at `https://<username>.github.io/<repo-name>/`.

## Structure

```
index.html                   Landing page
styles/colors_and_type.css   Design tokens (colors, fonts, spacing)
assets/
  logo.svg                   TrailFreaks logo mark
  app-icon.png               Full app icon (raster)
  app-store-black.svg        App Store badge, dark
  app-store-white.svg        App Store badge, light
  screenshots/*.png          App screenshots used on the page
```

Fonts are loaded from Google Fonts — an internet connection is required on first load.
