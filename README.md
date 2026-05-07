# Power Flight Golf — Website

Official website for **Power Flight Golf**, a golf instruction and coaching business based in Riverview, FL.

🌐 **Live site:** https://YOUR-USERNAME.github.io/powerflightgolf

---

## 📁 Repository Structure

```
powerflightgolf/
├── index.html          ← Main website (single file, self-contained)
├── images/             ← Add your gallery photos here
│   ├── gallery-1.jpg
│   ├── gallery-2.jpg
│   └── ... (up to gallery-6.jpg)
├── .nojekyll           ← Required for GitHub Pages (already included)
└── README.md           ← This file
```

---

## 🚀 Deploying to GitHub Pages

1. Create a new repository at [github.com/new](https://github.com/new)
   - Name it `powerflightgolf` (or anything you prefer)
   - Set it to **Public**
2. Upload all files in this folder to the repo root
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose branch `main`, folder `/ (root)` → **Save**
6. Your site will be live at `https://YOUR-USERNAME.github.io/powerflightgolf`

### Custom Domain (powerflightgolf.com)
To connect your domain:
1. Add a `CNAME` file to the repo containing just: `powerflightgolf.com`
2. In your domain registrar (e.g. GoDaddy), set DNS:
   - A record → `185.199.108.153`
   - A record → `185.199.109.153`
   - A record → `185.199.110.153`
   - A record → `185.199.111.153`
3. In GitHub Pages settings, enter your custom domain

---

## ✏️ Customization Checklist

### Before going live, update these in `index.html`:

- [ ] **Google Calendar** — Find `YOUR_CALENDAR_ID` and replace with your actual Google Calendar embed URL
  - Google Calendar → Settings → [Your Calendar] → Integrate Calendar → Embed Code
- [ ] **Google Forms** — Find `YOUR_FORM_ID` and replace with your actual Google Forms embed URL
  - Google Forms → Send button → Embed tab → copy the `src` URL
- [ ] **Social Media** — Update Facebook, Instagram, and YouTube links with your actual profile URLs
- [ ] **Gallery Photos** — Add photos named `gallery-1.jpg` through `gallery-6.jpg` into an `images/` folder

---

## 📞 Contact

- **Phone:** (501) 463-6673
- **Email:** info@powerflightgolf.com
- **Location:** Riverview, FL 33579
