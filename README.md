# Chaitali Arya — Portfolio

Personal AI/ML portfolio website.

## Deploy on Vercel

### Option 1: Drag & Drop (Fastest)
1. Go to [vercel.com](https://vercel.com) → Log in
2. Click **Add New → Project**
3. Drag the entire `portfolio` folder into the upload area
4. Click **Deploy** — done!

### Option 2: Via GitHub (Recommended for updates)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → **Add New → Project**
3. Import your GitHub repo
4. Vercel auto-detects it as a static site
5. Click **Deploy**

Every `git push` to `main` will auto-redeploy.

## Customization

- **Colors**: Edit the `:root` CSS variables at the top of `index.html`
- **Content**: All sections are clearly labeled with comments
- **Photo**: Add your photo by replacing the stat grid area with an `<img>` tag
- **Projects**: Update the project cards in the `#projects` section

## Structure

```
portfolio/
├── index.html    ← entire portfolio (single file, no build step needed)
├── vercel.json   ← Vercel deployment config
└── README.md     ← this file
```
