# Swathi Kannan — Lead Interior Designer Portfolio

Personal portfolio website for **Swathi Kannan**, Lead Interior Designer. Built with pure HTML, CSS and JavaScript. No frameworks, no build step, no backend — deploy anywhere instantly.

---

## Files

```
swathi-portfolio/
├── index.html                        ← Main website
├── style.css                         ← All styles
├── script.js                         ← Interactions & animations
├── README.md                         ← This file
└── assets/
    ├── images/
    │   ├── hero-interior.jpg         ← Hero background (replace me)
    │   ├── rove-business-bay.jpg     ← Project 1 image (replace me)
    │   ├── hospitality-project.jpg   ← Project 2 & 6 image (replace me)
    │   ├── luxury-villa.jpg          ← Project 3 image (replace me)
    │   ├── vvip-palace.jpg           ← Project 4 image (replace me)
    │   ├── workplace-office.jpg      ← Project 5 image (replace me)
    │   └── profile-photo.jpg         ← Your headshot (replace me)
    ├── pdf/
    │   ├── Swathi_Kannan_CV.pdf               ← Your CV (replace me)
    │   ├── Swathi_Kannan_Hospitality_Portfolio.pdf   ← (replace me)
    │   └── Swathi_Kannan_Residential_Portfolio.pdf  ← (replace me)
    └── icons/                        ← Favicon, app icons (optional)
```

---

## 1 — How to Replace Images

1. **Export your project renders or photography** at a minimum of 2000px wide.
2. **Rename each file** to match the placeholder names exactly (e.g. `hero-interior.jpg`). Filenames are case-sensitive.
3. **Copy your files** into `/assets/images/`, overwriting the placeholders.
4. Recommended image formats: **JPG** for photography, **WebP** for smaller file sizes.
5. For the hero image, use a landscape-oriented, high-quality interior photograph with dark tones — the overlay is designed for this.
6. For project cards, portrait orientation (4:5 ratio) works best.

**Tip:** If you want to use WebP for performance, rename the file extension and update `index.html` to match. Example: change `hero-interior.jpg` to `hero-interior.webp` in both the file and in `index.html`.

---

## 2 — How to Replace PDFs

1. Export your portfolio and CV as PDF.
2. Name them exactly:
   - `Swathi_Kannan_CV.pdf`
   - `Swathi_Kannan_Hospitality_Portfolio.pdf`
   - `Swathi_Kannan_Residential_Portfolio.pdf`
3. Copy them into `/assets/pdf/`, overwriting the placeholders.

The download buttons in the website already link to these exact paths — no code changes needed.

---

## 3 — How to Deploy to GitHub Pages (Free Hosting)

### Step 1 — Create a GitHub account
If you do not have one, go to [https://github.com](https://github.com) and sign up for free.

### Step 2 — Create a new repository
1. Click the **+** button → **New repository**
2. Name it: `swathi-kannan-portfolio` (or any name you prefer)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload your files
1. Click **Add file** → **Upload files**
2. Drag and drop the entire `swathi-portfolio` folder contents (not the folder itself — upload all files and the `assets/` folder directly)
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings** → **Pages** (in the left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch and **/ (root)** folder
4. Click **Save**

### Step 5 — Visit your website
After 1–3 minutes, your site will be live at:
```
https://YOUR-GITHUB-USERNAME.github.io/swathi-kannan-portfolio/
```
Replace `YOUR-GITHUB-USERNAME` with your actual GitHub username.

---

## 4 — How to Connect a Custom Domain Later

If you want a custom domain (e.g. `swathikannan.com`):

### Step 1 — Purchase a domain
Buy from any registrar: Namecheap, Google Domains, GoDaddy, or Porkbun.

### Step 2 — Add a CNAME file to your repository
1. In your GitHub repository, click **Add file** → **Create new file**
2. Name it: `CNAME` (no extension)
3. Add your domain as the content (one line, no www):
   ```
   swathikannan.com
   ```
4. Commit the file

### Step 3 — Configure DNS with your registrar
Add these DNS records in your domain registrar's settings:

**A Records** (point to GitHub's servers):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**CNAME Record** (optional, for www):
```
www → YOUR-GITHUB-USERNAME.github.io
```

### Step 4 — Enable HTTPS
In GitHub → Settings → Pages, check **Enforce HTTPS** once the domain is verified (usually takes a few minutes to a few hours).

---

## 5 — How to Create a QR Code for Your CV

Once your website is live on GitHub Pages (or a custom domain), create a QR code to embed in your CV:

### Free option (no account needed):
1. Go to [https://qr-code-generator.com](https://qr-code-generator.com)
2. Paste your website URL
3. Choose **PNG** or **SVG** format
4. Download the QR code

### Design tips for your CV:
- Use **SVG** format if your CV is vector-based (Illustrator, Figma)
- Use **PNG** at 300 dpi minimum for print
- Add a caption beneath the QR code: `Portfolio · swathikannan.com` or your GitHub Pages URL
- Place it in the header or footer of your CV alongside your contact details

---

## Customisation Tips

### Update contact details
Open `index.html` and search for `swati.kannan94@gmail.com` — update to your preferred email.

### Change the brass accent colour
Open `style.css` and update:
```css
--brass: #B8965A;
--brass-light: #D4AF78;
```

### Add a new project
Copy any `<article class="project-card">` block in `index.html`, update the image, title, location, tags and description.

### Add Google Analytics
Paste your GA4 tag just before `</head>` in `index.html`.

---

## Performance Notes

- All animations use CSS transitions and the Intersection Observer API — no jQuery, no heavy libraries.
- Images are lazy-loaded (`loading="lazy"`) on all project cards.
- Fonts are loaded from Google Fonts (EB Garamond + Inter). If you want full offline capability, download and self-host them.

---

*Built for Swathi Kannan — Lead Interior Designer, Doha, Qatar.*
