# AIToolsReview — GitHub Pages Site

A free, fast, AdSense-ready website for AI tool reviews.

---

## How to deploy (step by step, no coding needed)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up for a free account.

### Step 2 — Create a new repository
1. Click the "+" icon → "New repository"
2. Name it: `yourusername.github.io` (replace with your actual GitHub username)
3. Set it to **Public**
4. Click "Create repository"

### Step 3 — Upload your files
1. Click "uploading an existing file" on the repo page
2. Drag and drop ALL the files and folders from this zip
3. Click "Commit changes"

### Step 4 — Enable GitHub Pages
1. Go to your repo → Settings → Pages
2. Under "Source" select: Deploy from a branch → main → / (root)
3. Click Save

Your site will be live at: `https://yourusername.github.io` within 1-2 minutes.

### Step 5 — Add a custom domain (~$12/year)
1. Buy a domain at https://namecheap.com (e.g. aitoolsreview.com)
2. In Namecheap DNS settings, add a CNAME record pointing to `yourusername.github.io`
3. In GitHub Pages settings, enter your custom domain
4. Check "Enforce HTTPS"

---

## How to publish articles

1. Go to `yourdomain.com/admin`
2. Password: `admin123` (keep this private — don't share your site's admin URL)
3. Click "+ New article"
4. Paste your AI-generated article into the content box
5. Fill in title, category, excerpt, and meta description
6. Click "Publish"

The article appears on your homepage instantly.

---

## How to add Google AdSense

1. Go to https://adsense.google.com and apply with your domain
2. Once approved, copy your AdSense code snippet
3. Open `index.html` and find the comment: `<!-- Ad slot -->`
4. Replace the placeholder div with your AdSense code
5. Re-upload index.html to GitHub

---

## Files in this project

| File | Purpose |
|------|---------|
| index.html | Homepage — shows all articles |
| admin/index.html | Private admin panel to publish articles |
| about.html | About page (required for AdSense) |
| contact.html | Contact page (required for AdSense) |
| privacy.html | Privacy Policy (required for AdSense) |
| disclaimer.html | Disclaimer (required for finance content) |
| sitemap.xml | Helps Google find your pages |
| robots.txt | Tells Google what to index |

---

## Things to update before going live

- [ ] Replace `yourdomain.com` in sitemap.xml with your real domain
- [ ] Replace `yourdomain.com` in robots.txt with your real domain
- [ ] Change admin password in admin/index.html (search for `admin123`)
- [ ] Connect Formspree to the contact form (free at formspree.io)
- [ ] Add Google Analytics script to index.html head
- [ ] Apply for Google AdSense once you have 15-20 articles published
