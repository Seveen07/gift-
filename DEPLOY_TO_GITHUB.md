# Deploy Your Gift to GitHub 🎁

## Step-by-Step Guide

### 1. Create a GitHub Account (if you don't have one)
- Go to https://github.com
- Click "Sign up"
- Follow the setup steps

### 2. Create a New Repository

1. Click the **+** icon in the top-right corner
2. Select **New repository**
3. Name it: `gift-for-aya` (or any name)
4. Set to **Public** (so you can share the link)
5. Click **Create repository**

### 3. Upload Files Using Git

Open PowerShell and run these commands:

```powershell
# Navigate to your project folder
cd "C:\Users\Ejay\07 Software System for Testing\gift-for-her"

# Initialize git
git init

# Add all files
git add .

# Create a commit
git commit -m "A special gift for Aya"

# Add remote repository
git remote add origin https://github.com/YOUR_USERNAME/gift-for-aya.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll to **Pages** section
4. Under "Build and deployment"
5. Select **Deploy from a branch**
6. Choose **main** branch
7. Click **Save**

Wait 1-2 minutes for it to deploy.

### 5. Get Your Link

Your website will be available at:
```
https://YOUR_USERNAME.github.io/gift-for-aya/
```

Example: `https://ejay1234.github.io/gift-for-aya/`

---

## Adding Photos Before Deploying

**Important:** Add photos to the memories section BEFORE pushing to GitHub.

See `HOW_TO_ADD_PHOTOS.md` for detailed instructions.

---

## Sending It to Aya

1. Share the link with her
2. She can open it on any device
3. No installation needed!

---

## Making Updates Later

If you want to change something:

```powershell
cd "C:\Users\Ejay\07 Software System for Testing\gift-for-her"

# Make your changes to index.html

git add .
git commit -m "Update: added new message"
git push
```

---

## Common Issues

**"Repository not found"**
- Make sure you replace `YOUR_USERNAME` with your actual GitHub username

**Page says "404"**
- Wait a few minutes for GitHub Pages to build
- Check that your repository is public

**Images not showing**
- Make sure image URLs are correct (should start with http:// or https://)
- Test the URL in a browser to verify it works

---

**Ready? Let's do this! 🚀**

Let me know when you've uploaded the photos and I'll help you finalize everything!
