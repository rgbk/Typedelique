# 🚀 Deploy to GitHub Pages - Quick Guide

## Step 1: Add Files to Your Repo

```bash
# Navigate to your local Typedelique repo
cd /path/to/Typedelique

# Download these files from Claude and add them:
# - index.html (the main app)
# - README.md (the repo description)

# Add and commit
git add .
git commit -m "Add Typedelique interactive typography app"
git push origin main
```

## Step 2: Enable GitHub Pages

1. Go to https://github.com/rgbk/Typedelique/settings/pages
2. Under "Source", select: **main** branch
3. Click **Save**
4. Wait 1-2 minutes

## Step 3: Visit Your Live Site

Your app will be live at:
**https://rgbk.github.io/Typedelique/**

## 🎉 Done!

The video will work perfectly because you're self-hosting (no CSP restrictions).

---

## Optional: Custom Domain

If you want to use your own domain:
1. Add a `CNAME` file with your domain
2. Configure DNS settings
3. GitHub Pages will handle HTTPS automatically

---

**Need help?** Just ask in the chat!
