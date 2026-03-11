# Brandon Deurbrouck — Photography Portfolio

A three-page static photography portfolio and print shop.

## Structure

```
brandon-deurbrouck/
├── index.html        # Homepage (hero, gallery preview, prints preview, about, contact)
├── gallery.html      # Full filterable gallery
├── prints.html       # Prints shop with size/price selector
├── images/           # ← ADD YOUR IMAGES HERE
│   ├── hero.jpg
│   ├── photo-1.jpg
│   ├── photo-2.jpg
│   ├── photo-3.jpg
│   ├── photo-4.jpg
│   ├── photo-5.jpg
│   ├── photo-6.jpg
│   ├── photo-7.jpg
│   ├── photo-8.jpg
│   ├── photo-9.jpg
│   ├── print-1.jpg
│   ├── print-2.jpg
│   ├── print-3.jpg
│   └── about.jpg
└── README.md
```

## Images needed

| File | Used for |
|------|----------|
| `hero.jpg` | Hero section background (right panel) |
| `photo-1.jpg` — `photo-9.jpg` | Gallery images |
| `print-1.jpg` | Stars Over Lower print |
| `print-2.jpg` | Twinkle & Taillights print |
| `print-3.jpg` | Alone on 40 print |
| `about.jpg` | About section portrait |

**Recommended sizes:** Hero and about images at 1400px wide minimum. Gallery/print images at 1200px wide minimum. JPG quality 80–85% is fine.

## Deploying to Netlify

1. Go to [netlify.com](https://netlify.com) and sign up / log in
2. From the dashboard, drag and drop this entire folder onto the page
3. Done — Netlify gives you a live URL instantly

### To connect to GitHub instead:
1. Push this folder to a GitHub repo
2. In Netlify: **Add new site → Import from Git**
3. Select your repo — Netlify auto-deploys on every push

### Custom domain:
In Netlify: **Site settings → Domain management → Add custom domain**
Point your domain's DNS to Netlify's nameservers and HTTPS is set up automatically.

## Fonts
Loaded from Google Fonts (Playfair Display + DM Sans) — no local font files needed.

## Notes
- No build step, no dependencies — pure HTML/CSS/JS
- GSAP (ScrollTrigger) loaded from Cloudflare CDN
- Works offline once images are added locally
