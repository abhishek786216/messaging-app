# FlashChat Web Version

This directory contains the web platform files for the FlashChat Flutter application.

## Files:
- `index.html` - Main web entry point for Flutter web app
- `manifest.json` - Web app manifest for PWA functionality  
- `favicon.png` - Web app favicon
- `icons/` - Progressive Web App icons

## Building for Web:
```bash
flutter build web --release --base-href "/messaging-app/"
```

The built files will be in `build/web/` directory and deployed automatically via GitHub Actions to GitHub Pages.
