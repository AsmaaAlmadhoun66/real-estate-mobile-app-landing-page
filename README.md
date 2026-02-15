# Angel Real Estate - Mobile App Landing Page

A responsive, bilingual (English / Arabic RTL) landing page template for showcasing a real estate owners mobile application. Built with vanilla HTML, CSS, and jQuery—no build step required.

---

## Suggested GitHub Title & Repo Name

**Repository name (developer-friendly & SEO):**  
`real-estate-mobile-app-landing-page`

**Alternative names:**
- `property-owners-app-landing-template`
- `responsive-real-estate-app-landing-html`
- `html-css-mobile-app-landing-template`

**Why these work:** Clear keywords (`real estate`, `mobile app`, `landing page`, `template`, `responsive`, `html`) help developers and search engines understand the project at a glance.

---

## Features

### App Features (Product)

- **View a summary** — Clear statistics and overview of all property data
- **Quick access** — Fast access to all real estate with full property details
- **View real estate contracts** — Browse and review contracts for all properties
- **Tenant data review** — Access and manage tenant information in one place
- **Unified experience** — Same login and data as the Angel portal; app and web work together

### Landing Page Features

- **Fully responsive** — Mobile-first, tablet- and desktop-ready; retina/hi-DPI friendly
- **Bilingual** — English (LTR) and Arabic (RTL) via separate pages with language switcher
- **Smooth UX** — Preloader, smooth scroll, back-to-top, sticky nav with section highlighting
- **Animated sections** — Scroll-triggered animations (AOS)
- **Carousels** — App screens gallery and testimonials (Owl Carousel)
- **Contact / newsletter** — Email subscription form (Mailchimp-ready)
- **App store CTAs** — App Store and Play Store download badges
- **Social links** — Footer and hero social icons (Facebook, Twitter, Instagram, YouTube)
- **Semantic HTML5** — Clean structure and basic IE fallbacks

---

## Tech Stack & Libraries

### Core

| Technology | Purpose |
|------------|--------|
| **HTML5** | Structure, semantic sections, IE conditionals |
| **CSS3** | Layout, typography, responsive breakpoints, custom grid |
| **JavaScript (ES5)** | Interactivity, no framework |

### CSS

| Resource | Role |
|----------|------|
| **Normalize.css** | Reset / base styles (in `base.css`) |
| **Font Awesome** | UI and social icons |
| **Micons / IcoMoon** | Additional icon set |
| **Google Fonts** | Roboto, Tajawal (Latin + Arabic) |

### JavaScript

| Library | Version / Note | Use |
|--------|----------------|-----|
| **jQuery** | 2.1.3 | DOM, events, animations |
| **Modernizr** | — | Feature detection |
| **Pace.js** | — | Page load progress / preloader |
| **AOS** (Animate On Scroll) | — | Scroll-triggered animations |
| **Owl Carousel** | 2.2.0 | App screens & testimonials carousels |
| **Waypoints** | 4.0.0 | Section detection, nav highlight on scroll |
| **jQuery Placeholder** | 2.1.2 | Placeholder polyfill for older browsers |
| **FitVids** | 1.1 | Responsive embedded videos |
| **ajaxChimp** | — | Mailchimp newsletter form (optional) |
| **Lity** | 1.6.6 | Lightbox (images/iframes) |
| **Parallax.js** | 1.4.2 | Parallax backgrounds (if used) |

### Skills Demonstrated

- Responsive design (fluid grid, media queries)
- RTL layout and bilingual content (EN/AR)
- Accessibility-minded markup and structure
- Performance: preloader, minimal dependencies
- Integration points: Mailchimp, app store links, contact info

---

## Project Structure

```
├── index.html          # English (LTR)
├── index-rtl.html      # Arabic (RTL)
├── css/
│   ├── base.css        # Reset + grid + base
│   ├── base-rtl.css    # RTL base
│   ├── vendor.css      # AOS, Owl, Lity
│   ├── main.css        # Theme (EN)
│   ├── main-rtl.css    # Theme (RTL)
│   ├── fonts.css       # Font setup
│   ├── font-awesome/   # Font Awesome
│   └── micons/         # Micons / IcoMoon
├── js/
│   ├── jquery-2.1.3.min.js
│   ├── modernizr.js
│   ├── pace.min.js
│   ├── plugins.js      # Waypoints, Owl, Placeholder, FitVids, ajaxChimp, Lity, Parallax, AOS
│   └── main.js         # App logic (preloader, menu, carousels, smooth scroll, Mailchimp)
├── images/             # App screens, avatars, graphics
├── readme.txt          # Original notes (Mailchimp, license)
└── README.md           # This file
```

---

## Getting Started

1. **Clone or download** the repo.
2. **Open in browser:**  
   - English: `index.html`  
   - Arabic: `index-rtl.html`
3. **Optional — Mailchimp:**  
   - In `js/main.js`, set `cfg.mailChimpURL` to your Mailchimp form action URL.  
   - Uncomment `ssAjaxChimp()` inside `ssInit()`.
4. **Optional — App links:**  
   - Replace `#` on App Store / Play Store buttons with your real URLs.
5. **Optional — Contact:**  
   - Update email and phone in the footer (`index.html` and `index-rtl.html`).

No build tools or server required for local use.

---

## Customization

- **Colors / fonts:** Edit `css/main.css` (and `main-rtl.css` for RTL).
- **Content:** Edit `index.html` and `index-rtl.html` (copy, sections, links).
- **Images:** Replace assets in `images/` and update paths in HTML.
- **Sections:** Add/remove sections and mirror in `index-rtl.html` and in the header/footer nav.

---

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Basic support for older IE via conditionals and polyfills (e.g. placeholder)

---

## License

See `readme.txt` for the original license (Creative Commons Attribution 3.0) and attribution details.

---

## Credits

- **Template base:** Asaas Mobile App (Styleshout)
- **Fonts:** Google Fonts (Roboto, Tajawal)
- **Icons:** Font Awesome, Micons, IcoMoon
- **JS:** jQuery, AOS, Owl Carousel, Waypoints, and other libraries listed above (see `readme.txt` and comments in `js/plugins.js` for links and licenses).
