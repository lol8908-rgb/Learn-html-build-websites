# Lesson 07 — Publishing Your Website

## Share Your Website with the World

You've learned HTML and built some amazing pages. Now let's get them online so others can see them!

---

## What Does Publishing Mean?

Publishing means uploading your website to the internet so anyone can visit it.

Instead of keeping your files on your computer, you put them on a web server (a computer that's always on, connected to the internet).

---

## The Process

```
Your Computer → Upload → Web Server → Everyone Can See It
    (files)       (files)     (web host)      (on the internet)
```

---

## Free Options to Publish Your Website

### Option 1: GitHub Pages (Recommended for Beginners)

GitHub Pages is **free** and perfect for learning. It hosts your website directly from GitHub.

**Steps:**
1. Create a free GitHub account at https://github.com
2. Create a new repository named `yourusername.github.io`
3. Upload your HTML files
4. Your site is live at `https://yourusername.github.io`

**Example:** If your username is "john123", visit `https://john123.github.io` to see your site!

**Pros:** Free, easy, no ads  
**Cons:** Less control over backend settings

### Option 2: Netlify (Very Beginner-Friendly)

Netlify is free and easy to use.

**Steps:**
1. Visit https://netlify.com
2. Sign up (free account)
3. Drag and drop your HTML files onto Netlify
4. Your site is live with a free domain!

**Pros:** Super easy, automatic updates  
**Cons:** No server-side code (you'll learn about that later)

### Option 3: Vercel (Also Very Easy)

Similar to Netlify.

**Steps:**
1. Visit https://vercel.com
2. Sign up with GitHub
3. Connect your GitHub repository
4. Your site auto-publishes!

**Pros:** Automatic updates when you push to GitHub  
**Cons:** Requires GitHub knowledge

### Option 4: Traditional Web Hosting

Services like Bluehost, GoDaddy, or HostGator let you host websites.

**Pros:** Full control, custom domain  
**Cons:** Costs money ($5-15/month typically)

---

## Preparing Your Website

Before publishing, organize your files:

```
my-website/
├── index.html (your main page)
├── about.html
├── contact.html
├── images/
│   ├── logo.png
│   ├── photo1.jpg
│   └── photo2.jpg
├── css/
│   └── style.css (for later!)
└── pages/
    └── blog.html
```

**Important:** Name your main page `index.html`. Servers look for this file first when someone visits your site.

---

## Step-by-Step: Publish on GitHub Pages

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Sign up (it's free!)
3. Verify your email

### Step 2: Create a Repository
1. Click "New" to create a repository
2. Name it `yourusername.github.io` (replace with your actual username)
3. Keep it public
4. Click "Create repository"

### Step 3: Upload Your Files
1. Click "Add file" → "Upload files"
2. Select all your HTML, CSS, images, and other files
3. Click "Commit changes"

### Step 4: Visit Your Website
1. Go to `https://yourusername.github.io`
2. Your website is live! 🎉

**Wait:** It might take a few minutes to appear.

---

## Step-by-Step: Publish on Netlify

### Step 1: Create an Account
1. Visit https://netlify.com
2. Click "Sign up"
3. Sign up with GitHub (or email)

### Step 2: Upload Your Site
1. Click "New site from Git" or drag and drop folder
2. Select your repository (if you connected GitHub)
3. Or drag your entire website folder onto the page

### Step 3: Wait for Deployment
1. Netlify automatically builds your site
2. You'll get a free URL like `https://random-name.netlify.app`
3. Visit it — your site is online!

### Step 4: Custom Domain (Optional)
1. Go to Site settings
2. Add a custom domain if you own one
3. Point your domain to Netlify (they explain how)

---

## Important Tips

✅ **Do:**
- Test your website on your computer first
- Use `index.html` as your main page
- Make sure all links work
- Check that all images appear
- Test on different browsers (Chrome, Firefox, Safari)

❌ **Don't:**
- Upload before testing
- Use absolute paths in links like `C:\Users\YourName\...`
- Use spaces in file names (use `my-photo.jpg` not `my photo.jpg`)
- Use uppercase in file names for links (`index.html` not `Index.HTML`)

---

## Testing Before Publishing

**Checklist:**
- [ ] All pages load without errors
- [ ] All links work (both internal and external)
- [ ] All images appear
- [ ] Forms have submit buttons
- [ ] Navigation between pages works
- [ ] Website looks good in your browser

---

## After Publishing: Keeping Your Site Updated

### On GitHub:
1. Edit your files locally on your computer
2. Upload the new version to GitHub
3. Your site updates automatically

### On Netlify:
1. If connected to GitHub, changes auto-deploy
2. Or drag new files onto Netlify to update

---

## Common Issues & Fixes

### Issue: Links Don't Work
**Fix:** Make sure file names match exactly (case-sensitive on servers!)
```
Wrong: <a href="About.html">
Right: <a href="about.html">
```

### Issue: Images Don't Show
**Fix:** Check the image path
```html
Wrong: <img src="C:\Users\John\desktop\photo.jpg">
Right: <img src="images/photo.jpg">
```

### Issue: Website Not Appearing After Upload
**Fix:** It takes a few minutes. Wait and refresh your browser.

---

## What's Next After Publishing?

Congratulations! You've learned HTML and published your first website! 🚀

Next steps to improve:
- **Learn CSS** — Make your website beautiful with colors, fonts, and layouts
- **Learn JavaScript** — Make your website interactive with buttons and animations
- **Learn Responsive Design** — Make your site look great on phones and tablets
- **Learn About Forms & Backends** — Actually receive form submissions

---

## Summary

- Publishing puts your website on the internet
- GitHub Pages, Netlify, and Vercel are free options
- Name your main page `index.html`
- Organize files in folders (images, css, pages, etc.)
- Test everything before publishing
- Use relative paths for links and images
- Your site can be updated anytime by uploading new files

---

[← Previous Lesson](06-forms.md)

---

## 🎉 Congratulations!

You've completed all 7 HTML lessons! You now know:
- What HTML is and how it works
- How to create web pages
- How to structure content with headings and paragraphs
- How to add links and images
- How to organize information with lists and tables
- How to create interactive forms
- How to publish your website for the world to see

**You're an HTML developer!** Keep building and learning. Happy coding! 💻
