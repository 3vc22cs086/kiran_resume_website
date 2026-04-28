# Kedarnath Shastry PBM — Portfolio Website

A clean, responsive personal portfolio website.

## File Structure

```
portfolio/
├── index.html       ← Main HTML page
├── css/
│   └── style.css    ← All styles
├── js/
│   └── main.js      ← Interactivity (nav, animations)
└── README.md
```

## How to Deploy

### Option 1 — GitHub Pages (Free, Recommended)

1. Create a GitHub account at https://github.com
2. Create a new repository named: `kedarnath-portfolio` (or any name)
3. Upload all files keeping the folder structure intact
4. Go to **Settings → Pages**
5. Under "Source", select **main branch** and click Save
6. Your site will be live at: `https://yourusername.github.io/kedarnath-portfolio`

### Option 2 — Netlify (Free, Drag & Drop)

1. Go to https://netlify.com and sign up
2. Click **"Add new site" → "Deploy manually"**
3. Drag and drop the entire `portfolio/` folder
4. Your site goes live instantly with a free URL like `https://kedarnath.netlify.app`
5. You can set a custom domain from the Netlify dashboard

### Option 3 — Vercel (Free)

1. Go to https://vercel.com and sign up
2. Import your GitHub repo or drag and drop files
3. Click Deploy — done!

### Option 4 — Run Locally

Just open `index.html` in any browser. No server needed.

## Customization Tips

- **Update LinkedIn/GitHub links** in `index.html` under the `#contact` section
- **Add a profile photo** by inserting an `<img>` tag in the hero section
- **Change accent color** by editing `--accent: #b35c2a;` in `css/style.css`
- **Add more projects** by copying a `.proj-card` block in `index.html`
