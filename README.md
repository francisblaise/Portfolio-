# Francis Agbo — Portfolio Website

A clean, dark editorial portfolio site built for hosting on Vercel.

## Files
- `index.html` — The entire site (HTML + CSS + JS, self-contained)
- `vercel.json` — Vercel deployment config

---

## Deploy to Vercel (3 ways)

### Option 1: Drag & Drop (Easiest — no account needed initially)
1. Go to [vercel.com](https://vercel.com) and sign up (free)
2. From your dashboard, click **"Add New → Project"**
3. Drag the entire `portfolio` folder into the upload zone
4. Click **Deploy** — done. You'll get a live URL like `francis-portfolio.vercel.app`

### Option 2: GitHub + Vercel (Recommended for easy updates)
1. Create a free GitHub account if you don't have one
2. Create a new repository called `portfolio`
3. Upload `index.html` and `vercel.json` to that repo
4. Go to [vercel.com](https://vercel.com), click **"Add New → Project"**
5. Connect your GitHub and select the `portfolio` repo
6. Click **Deploy** — future pushes to GitHub auto-deploy!

### Option 3: Vercel CLI
```bash
npm i -g vercel
cd portfolio
vercel
```
Follow the prompts — it deploys in under a minute.

---

## Customization

### Add a real photo
Replace the `FA` initials block in the `.portrait-box` div with:
```html
<img src="your-photo.jpg" alt="Francis Agbo" />
```
Upload your photo alongside `index.html`.

### Update research report links
Find the `.research-card` blocks and add `href` links once reports are public.

### Custom domain
In Vercel dashboard → your project → Settings → Domains → add your domain.

---

## Tech Stack
- Pure HTML/CSS/JS — zero dependencies, zero build step
- Google Fonts (Fraunces + Syne) loaded via CDN
- Fully responsive (mobile + desktop)
- Scroll animations via Intersection Observer API
