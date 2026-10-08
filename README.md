# GROZ v8 — Theme Contrast Fix

This build removes the WHITE theme option entirely.

## Theme behavior
- DARK: black/dark surfaces + white text.
- BRIGHT: white/light surfaces + black text.
- GROZ red accent remains red in both themes.
- All text, inputs, buttons, cards and modal controls use CSS theme variables so text never becomes black on a black surface.
- Settings contains only Dark and Bright, plus English/Bangla.
- Theme and language are saved in localStorage.

## Important
Replace `YOUR-DOMAIN.example` in `robots.txt` and `sitemap.xml` with the real GROZ domain before submitting the sitemap to Google Search Console.
