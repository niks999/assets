# Calendar Conflict Auto-Decliner

Professional website and resources for the Calendar Conflict Auto-Decliner Google Workspace add-on.

## Repository Structure

```
calendar-conflict-decliner/
├── index.html          # Main website (root for GitHub Pages)
├── privacy.html        # Privacy policy
├── styles.css          # Website styling
├── assets/
│   └── icons/          # Application icons
│       ├── calendar-plugin.png
│       └── calendar-plugin.svg
└── README.md           # This file
```

## GitHub Pages Deployment

### Setup Steps:
1. Rename repository to `calendar-conflict-decliner` on GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → main → `/ (root)`
4. Your site will be live in ~5 minutes

## Google Workspace Marketplace URLs

Your URLs for marketplace submission:

1. **Website URL**: `https://niks999.github.io/calendar-conflict-decliner/`

2. **Privacy Policy URL**: `https://niks999.github.io/calendar-conflict-decliner/privacy.html`

## Website Features

The website includes:
- ✅ Professional homepage with feature overview
- ✅ GDPR/CCPA compliant privacy policy  
- ✅ Contact email: `niks999@gmail.com`
- ✅ Responsive mobile-friendly design
- ✅ Google Workspace branding consistency

## Icon Assets

Icons are available via jsDelivr CDN:
- PNG: `https://cdn.jsdelivr.net/gh/niks999/calendar-conflict-decliner/assets/icons/calendar-plugin.png`
- SVG: `https://cdn.jsdelivr.net/gh/niks999/calendar-conflict-decliner/assets/icons/calendar-plugin.svg`

## Local Testing

To test locally:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## About the Add-on

Calendar Conflict Auto-Decliner is a Google Workspace add-on that automatically manages calendar scheduling conflicts by intelligently declining overlapping meetings while protecting important appointments.

Key features:
- Smart conflict detection
- Protected keyword filtering
- Configurable automation settings
- Dry-run preview mode
- Own meeting protection