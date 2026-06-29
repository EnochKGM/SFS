# Shield Facility Services — Official Website

> **Shielded. Secure. Serene.**  
> A modern, single-page business website for **Shield Facility Services**, a Bangalore-based facility management company offering security, housekeeping, pest control, plumbing, gardening, CCTV, electrical services, and STP/ETP cleaning.

---

## 🌐 Live Preview

<!-- Replace with your actual GitHub Pages / hosting URL -->
```
https://enochkgm.github.io/shield-facility-services/
```

---

## 📋 Overview

This is a fully static, single-file HTML website built for Shield Facility Services (SFS), a proprietorship run by **Mohanraju M**, based in Whitefield, Bangalore. The site acts as a professional digital presence — showcasing services, building trust, and converting visitors into leads via phone and contact form.

---

## ✨ Features

- **Dark / Light mode** — toggle persisted to `localStorage`
- **Animated particle background** — subtle canvas-based network effect
- **Smooth scroll navigation** — fixed navbar with hamburger menu on mobile
- **Hero section** — headline, stats bar (8+ services, 24/7, licensed)
- **Trust bar** — client segment logos (Homes, Offices, Hospitals, Malls, Schools)
- **Services grid** — 8 service cards: Security, Housekeeping, Pest Control, Plumbing, Gardening, CCTV, Electrical, STP/ETP Cleaning
- **Why Us section** — animated SVG orbit visual + value-proposition pills
- **Numbers / stats section** — key metrics at a glance
- **About section** — company story, proprietor card, capability badges
- **Testimonials** — 3 client reviews with star ratings
- **Team Gallery** — filterable photo grid (Security / Housekeeping / Technical / Other) with lightbox viewer
- **Contact section** — enquiry form + direct phone/email/location details
- **Mobile floating action button (FAB)** — sticky "Call Now" button on mobile
- **Scroll-reveal animations** — staggered fade-up on section entry
- **Fully responsive** — mobile-first layout using CSS Grid and `clamp()`

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Pure CSS3 (CSS custom properties, Grid, Flexbox) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — [Syne](https://fonts.google.com/specimen/Syne) & [Inter](https://fonts.google.com/specimen/Inter) |
| Graphics | Inline SVG icons + Canvas API (particle bg) |
| No dependencies | Zero frameworks, zero npm packages |

---

## 📁 File Structure

```
shield-facility-services/
├── index.html        # Entire website — single self-contained file
├── logo.png          # SFS logo (referenced in nav, hero, and why-us sections)
├── g1.jpeg           # Gallery photo
├── g2.jpeg           # Gallery photo
├── g3.jpeg           # Gallery photo
└── README.md
```

> All CSS and JavaScript are embedded directly inside `index.html` for zero-dependency deployment.

---

## 🖼️ Adding Gallery Photos

Open `index.html` and find the `GALLERY_PHOTOS` array near the bottom of the `<script>` block:

```javascript
const GALLERY_PHOTOS = [
  { src: "your-photo.jpg", name: "Staff Name", role: "Job Title", cat: "security" },
  // ...
];
```

**Category options:** `"security"` | `"housekeeping"` | `"technical"` | `"other"`

Place image files in the same directory as `index.html` and add entries to the array.

---

## 🚀 Deployment

### GitHub Pages

1. Push the repo to GitHub.
2. Go to **Settings → Pages**.
3. Set source to `main` branch, `/ (root)`.
4. Your site will be live at `https://<username>.github.io/<repo-name>/`.

### Any Static Host

Upload all files (`index.html`, `logo.png`, `g1.jpeg`, etc.) to any static hosting provider — Netlify, Vercel, Hostinger, or a shared cPanel host. No build step required.

---

## 📞 Business Contact

| | |
|---|---|
| 📱 Phone | +91 6362675057 / +91 9980490637 |
| 📧 Email | shieldfacilityservice@gmail.com |
| 📍 Address | Whitefield, Bangalore – 560066 |

---

## 🎨 Customisation Guide

| What to change | Where to find it |
|---|---|
| Brand colour (cyan `#0eb8d8`) | `:root` CSS variables — `--brand`, `--brand-dk` |
| Company name / tagline | `<title>` tag and `.hero-h` section |
| Service descriptions | `.svc-card` blocks inside `#services` |
| Testimonials | `.tcard` blocks inside `#testimonials` |
| Stats / numbers | `.hstat` (hero) and `.ncell` (numbers section) |
| Contact details | `#contact` section + footer `.fcol` |
| Gallery images | `GALLERY_PHOTOS` array in the `<script>` block |

---

## 📄 License

This website was built for **Shield Facility Services**.  
© 2025 Shield Facility Services. Proprietor: Mohanraju M. All rights reserved.
