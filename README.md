# Going for Gold - GitHub Pages Site

Simple skeleton website for your app. Fill in the placeholders with your content.

## Files

- `index.html` - Home page
- `help.html` - Help and FAQ
- `privacy.html` - Privacy policy (required for App Store)
- `contact.html` - Contact/support page
- `style.css` - Basic styling

## How to Deploy to GitHub Pages

1. Create a new GitHub repository (e.g., `going-for-gold-site`)

2. Push these files:
```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/going-for-gold-site.git
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to repository Settings
   - Pages section (left sidebar)
   - Source: Deploy from branch
   - Branch: main, folder: / (root)
   - Save

4. Your site will be live at:
   `https://YOUR-USERNAME.github.io/going-for-gold-site/`

## What to Add

1. Fill in placeholder text marked with `[brackets]`
2. Add your app screenshots
3. Write your privacy policy details
4. Add your support email
5. Customize colors in `style.css` if desired

## For App Store Connect

Use these URLs:
- Support URL: `https://YOUR-USERNAME.github.io/going-for-gold-site/help.html`
- Privacy Policy URL: `https://YOUR-USERNAME.github.io/going-for-gold-site/privacy.html`
