# Arghadip Jana — Portfolio

Personal portfolio website for Arghadip Jana, Network Engineer & Cybersecurity Specialist.

## Deploy

### Netlify (Drag & Drop)
1. Go to [netlify.com](https://netlify.com) → Log in
2. Drag the entire `portfolio/` folder onto the Netlify dashboard
3. Done — live in seconds

### Netlify CLI
```bash
npm install -g netlify-cli
netlify deploy --dir . --prod
```

### Vercel
```bash
npm install -g vercel
vercel --name arghadip-portfolio
```

### GitHub Pages
1. Push this folder contents to a GitHub repo
2. Go to Settings → Pages → Source: root → Save
3. Live at `https://<username>.github.io/<repo>`

### Self-host (Nginx / Apache)
```bash
# Nginx: copy files to web root
cp index.html profile.jpg /var/www/html/
```

## Files
- `index.html` — Main portfolio page (self-contained)
- `profile.jpg` — Profile photo
- `_redirects` — Netlify SPA redirect rule
- `README.md` — This file
