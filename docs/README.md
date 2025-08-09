# Calendar Conflict Auto-Decliner Website

This directory contains the static website and privacy policy for the Calendar Conflict Auto-Decliner Google Workspace add-on.

## Files

- `index.html` - Main website homepage
- `privacy.html` - Privacy policy page
- `styles.css` - CSS styling for both pages

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Push this website directory to a GitHub repository
2. Go to repository Settings → Pages
3. Select source as "Deploy from a branch"
4. Choose main branch and /website folder
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free tier available)
1. Create account at [netlify.com](https://netlify.com)
2. Drag and drop the `website` folder to Netlify dashboard
3. Or connect to your GitHub repository for automatic deployments
4. Your site will get a random subdomain like `https://amazing-site-12345.netlify.app`

### Option 3: Vercel (Free tier available)
1. Create account at [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Set root directory to `website`
4. Deploy automatically

### Option 4: Firebase Hosting (Free tier available)
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Run `firebase init hosting` in the website directory
3. Set public directory to `.` (current directory)
4. Run `firebase deploy`

## GitHub Pages Deployment

### Setup Steps:
1. Push the assets repository to GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → main → `/docs`
4. Your site will be live in ~5 minutes

## Google Workspace Marketplace Requirements

Your URLs for marketplace submission:

1. **Website URL**: `https://niks999.github.io/assets/`

2. **Privacy Policy URL**: `https://niks999.github.io/assets/privacy.html`

## Ready for Deployment

The website is configured with:
- ✅ Contact email: `niks999@gmail.com` (in privacy policy)
- ✅ Professional design and content
- ✅ GDPR/CCPA compliant privacy policy
- ✅ Responsive mobile-friendly layout

## Local Testing

To test locally, simply open `index.html` in your web browser or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.