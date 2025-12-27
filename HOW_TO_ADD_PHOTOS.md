# How to Add Photos to Aya's Gift Website

## Option 1: Using Online Image URLs (Easiest for GitHub Pages)

1. Upload your photos from `C:\Users\Ejay\OneDrive\Documents\Aya` to an image hosting service like:
   - **Imgur.com** (free, no account needed)
   - **ImgBB.com** (free, simple)
   - **Google Drive** (share link)
   - **Cloudinary** (free tier)

2. Get the direct image URLs (links that end in .jpg, .png, etc.)

3. Edit the `index.html` file and find the memory cards section (around line 750)

4. Replace the placeholder cards with actual images using this format:

```html
<div class="memory-card">
    <img src="PASTE_IMAGE_URL_HERE" alt="Photo" class="memory-image">
</div>
```

Example:
```html
<div class="memory-card">
    <img src="https://imgur.com/abc123.jpg" alt="Aya" class="memory-image">
</div>
```

## Option 2: Using Local File Path (Works on Your Computer)

If you want it to work on your computer without uploading:

1. Copy your photos to: `c:\Users\Ejay\07 Software System for Testing\gift-for-her\photos\`

2. Create a `photos` folder in the gift-for-her directory if it doesn't exist

3. Edit the memory cards to use:

```html
<div class="memory-card">
    <img src="photos/photo1.jpg" alt="Aya" class="memory-image">
</div>
```

**Note:** Local paths won't work on GitHub Pages, so Option 1 is recommended for sharing.

## Option 3: Base64 Encoding (Advanced)

Embed images directly in HTML without external links (good for privacy):
- Use an online Base64 encoder
- Paste the encoded string into the `src` attribute

---

## Quick Steps to Deploy

1. **Get image URLs** from Imgur or ImgBB
2. **Edit the memory cards** in index.html with image URLs
3. **Commit and push to GitHub**
4. **Share the GitHub Pages link with Aya!**

## Recommended Photo Order

You have 6 photo slots. Consider ordering them by:
- Favorite photos
- Recent photos
- Different moods/expressions
- Mix of close-ups and full body shots

---

Need help? Just let me know which photos you want to add and I can help you embed them!
