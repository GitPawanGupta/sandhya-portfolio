# Portfolio Deployment Guide

## Option 1: GitHub Pages (Recommended)

### Steps:
1. Create a GitHub account at https://github.com
2. Create a new repository named `your-username.github.io`
3. Upload these files:
   - index.html
   - styles.css
   - script.js
   - README.md

4. Go to repository Settings → Pages
5. Select "main" branch as source
6. Your site will be live at: `https://your-username.github.io`

### Using Git Commands:
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/your-username/your-username.github.io.git
git push -u origin main
```

## Option 2: Netlify (Easiest)

### Steps:
1. Go to https://netlify.com
2. Sign up for free account
3. Click "Add new site" → "Deploy manually"
4. Drag and drop your project folder
5. Get instant live URL (e.g., `your-site.netlify.app`)
6. Optional: Add custom domain

## Option 3: Vercel

### Steps:
1. Go to https://vercel.com
2. Sign up with GitHub/Email
3. Click "New Project"
4. Import your GitHub repository or upload files
5. Click "Deploy"
6. Get live URL (e.g., `your-portfolio.vercel.app`)

## Custom Domain (Optional)

After deployment, you can add a custom domain like:
- `sandhyagupta.com`
- `sandhya-portfolio.com`

Most platforms offer free SSL certificates and custom domain support.

## Recommended: Netlify or GitHub Pages

Both are:
- ✅ Free forever
- ✅ Easy to use
- ✅ Automatic HTTPS
- ✅ Fast global CDN
- ✅ Perfect for portfolios
