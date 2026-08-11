# Nazihah Portfolio

A soft, modern pastel portfolio site for Nur Nazihah Nabila Binti Roslan — Human Resource
Management student and HR intern at Jabatan Pengairan dan Saliran (JPS) Negeri Perlis. Built as a
single static HTML page with Tailwind CSS and AOS (Animate On Scroll).

Live at [nazihah.site](https://www.nazihah.site).

## ✨ Features

- **Soft modern pastel design**: warm cream background, rose + sage accent palette, Fraunces
  serif headings paired with Plus Jakarta Sans body text
- **Responsive, card-light layout**: sections that don't need a card (like Work Experience and
  Awards) skip the boxed treatment on mobile so content has room to breathe
- **Apple-style bottom tab bar on mobile**: floating pill navigation with icons, active-section
  highlighting via `IntersectionObserver`, and safe-area padding for notched devices
- **Full sections**: Hero/profile photo, About/Profile summary, Work Experience, Skills & Tools,
  Education, Awards & Co-curricular, Contact + Reference
- **SEO/link-preview ready**: canonical URL, Open Graph + Twitter Card meta tags, favicon and
  apple-touch-icon

## 🚀 Getting Started

No build tools required — this is a static HTML site.

```bash
git clone https://github.com/HazeeqHaikal/nazihah_portfolio.git
cd nazihah_portfolio
python3 -m http.server 8000
```

Visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors

The palette is defined in the Tailwind config inside `index.html`:

```javascript
colors: {
    cream: { 50: '#FFFDFB', 100: '#FBF6EF', 200: '#F3E9DD', 300: '#E7D8C4' },
    rose:  { 50: '#FDF3F0', 400: '#DE8770', 500: '#C96C54' },
    sage:  { 50: '#F4F7F0', 400: '#8FB275', 500: '#729657' },
    ink:   { 900: '#2C2621', 700: '#544A3F', 500: '#7C7266' },
}
```

### Content

All content (profile, experience, skills, education, awards, contact, reference) lives directly in
`index.html`. The profile photo is at `assets/profile.jpg`.

## 📦 Dependencies

All loaded via CDN — no npm install needed:

- [Tailwind CSS](https://tailwindcss.com/) — utility-first CSS framework
- [AOS](https://michalsnik.github.io/aos/) — animate-on-scroll library
- [Google Fonts](https://fonts.google.com/) — Fraunces & Plus Jakarta Sans

## 🌐 Hosting

Served via GitHub Pages with a custom domain (`CNAME` → `www.nazihah.site`). Pushing to `main`
redeploys automatically.

## 📝 License

MIT — see [LICENSE](LICENSE).

## 👤 Author

**Nazihah** — content and profile owner
Site built &amp; maintained by [hazeeq.org](https://hazeeq.org) ([@HazeeqHaikal](https://github.com/HazeeqHaikal))
