# Alperen Duru - Academic Website

A clean, minimal academic website built with HTML and CSS.

## 🚀 Quick Setup (GitHub Pages)

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com) and click "Sign up"
2. Choose a username (this will be part of your URL: `username.github.io`)
3. Complete the registration

### Step 2: Create Your Website Repository
1. Click the **+** icon in the top right → **New repository**
2. **Important:** Name it exactly `YOUR_USERNAME.github.io` (replace YOUR_USERNAME with your actual GitHub username)
3. Keep it **Public**
4. Check "Add a README file"
5. Click **Create repository**

### Step 3: Upload Your Website Files
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop these files:
   - `index.html`
   - `style.css`
   - `photo.jpg` (your photo - optional)
   - `CV_Alperen_Duru.pdf` (your CV)
3. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to your repository **Settings** (tab at the top)
2. Scroll down to **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**

### Step 5: Visit Your Site!
After a few minutes, your site will be live at:
```
https://YOUR_USERNAME.github.io
```

---

## 📝 Customization Checklist

Before uploading, make these edits in `index.html`:

- [ ] **Photo**: Add a file named `photo.jpg` (square, at least 320x320px) or the placeholder initials will show
- [ ] **Google Scholar**: Replace `YOUR_ID` in the Google Scholar link with your actual ID, or remove the link
- [ ] **CV PDF**: Rename your CV file to `CV_Alperen_Duru.pdf` or update the link in the HTML
- [ ] **Publication links**: Uncomment and add PDF/arXiv links when available
- [ ] **About section**: Adjust the bio text if needed

---

## 🎨 Customization Tips

### Change the accent color
In `style.css`, find the `:root` section and change `--primary-color`:
```css
--primary-color: #bf5700; /* UT Austin burnt orange */
```

### Add a new publication
Copy an existing `.pub-item` div and update the content.

### Add more sections
Copy an existing `<section>` block and modify it.

---

## 📁 File Structure

```
your-repo/
├── index.html          # Main webpage
├── style.css           # Styling
├── photo.jpg           # Your photo (optional)
├── CV_Alperen_Duru.pdf # Your CV
└── README.md           # This file
```

---

## 🔗 Optional: Custom Domain

If you want a custom domain like `alperenduru.com`:
1. Buy a domain from Namecheap, Google Domains, etc.
2. In your repo, create a file called `CNAME` containing just your domain
3. Configure DNS at your domain provider to point to GitHub Pages
4. See [GitHub's guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

## 📧 Questions?

The website is pure HTML/CSS with no dependencies, so it's easy to modify. Just edit the files and push to GitHub - changes go live automatically in a few minutes.
