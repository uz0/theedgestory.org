# The Edge Story - Landing Page

🌌 Official landing page for The Edge Story - an endless story generation unit.

## Live Site

**Production**: https://theedgestory.org

## Features

- 🚀 Static HTML landing page
- 📱 Fully responsive design
- ⚡ Hosted on GitHub Pages
- 🔒 GDPR-compliant Privacy Policy
- 📜 Complete Terms of Service

## Pages

- **Home** (`index.html`) - Main landing page with cosmic theme
- **Privacy Policy** (`privacy-policy.html`) - GDPR compliance
- **Terms of Service** (`terms-of-service.html`) - Legal terms with IP ownership

## Development

This is a static site. To preview locally:

```bash
# Simple HTTP server (Python 3)
python3 -m http.server 8000

# Or with Node.js
npx serve .
```

Visit: http://localhost:8000

## Deployment

Automatically deployed to GitHub Pages via GitHub Actions on every push to `main`.

## DNS Configuration

For custom domain `theedgestory.org`:

1. Add GitHub Pages A records:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

2. Add CNAME for www subdomain:
   ```
   www  →  uz0.github.io
   ```

## License

MIT License - See LICENSE file for details
