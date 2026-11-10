# Brick & Mortar Constructions Website

Official website for **Brick & Mortar Constructions**, Chennai, Tamil Nadu, India.  
**Tagline:** TRANSPARENT. TIMELY. TRUSTED.  
**Founded:** 2010 by Er. Sankar K.  
**Official Portal:** [www.brickandmortarconstruction.com](http://www.brickandmortarconstruction.com)  
**Email:** [brickandmortar.construction@gmail.com](mailto:brickandmortar.construction@gmail.com)  
**Phone / WhatsApp:** +91 97887 93679 / +91 70927 94679  

---

## Architecture & Technology Stack
- **Pure Semantic HTML5** (W3C validated, zero external JavaScript frameworks, accessible ARIA roles).
- **Direct Page Navigation:** Each section is a dedicated page (`index.html`, `about.html`, `services.html`, `projects.html`, `packages.html`, `contact.html`) with instant redirect navigation and zero scrolling delays.
- **Modern Responsive CSS3** (Custom properties, grid bento layout, flexbox, pure CSS lightbox dialogs, print stylesheet).
- **No dependencies or build steps required.**

---

## Website Pages & Structure
```text
brick-and-mortar/
├── index.html            # Homepage (Hero, Stats, Featured Showcase, Quick Enquiry)
├── about.html            # About Us & Quality Assurance (History, Founder, 6 Quality Pillars)
├── services.html         # Our Services & 5-Step Working Process (Construction, Interiors, Renovation, Turnkey)
├── projects.html         # Project Types, Confirmed Projects & 13-Item Bento Gallery with Lightboxes
├── packages.html         # Construction Packages & Transparent Specifications (Basic, Standard, Premium)
├── contact.html          # Contact Us & Modern 6-Field Validated Enquiry Form (WhatsApp + Email)
├── style.css             # Main unified stylesheet across all pages
├── robots.txt            # Search engine crawling rules
├── sitemap.xml           # XML sitemap for search engine indexation
├── README.md             # Project documentation & deployment guide
├── images/               # Production brand & building assets
│   ├── logo.png          # Primary official brand logo
│   ├── logo-white.png    # White-contrast logo for dark backgrounds
│   ├── hero-banner-master.jpg # Full master composite banner for the homepage
│   ├── banner-elevation.jpg # Client 3D residential elevation featured in homepage hero & gallery
│   ├── hero-building.jpg # Hero banner contemporary residence
│   ├── founder-sankar.jpg# Founder portrait (Er. Sankar K.)
│   ├── service-*.jpg     # Service photography (Construction, Interiors, Renovation, Turnkey)
│   ├── type-*.jpg        # Project sector imagery (Residential, Institutional, Commercial, Healthcare)
│   ├── mudichur-*.jpg    # Mudichur project elevation & completed photos
│   ├── vengaivaasal-*.jpg# Vengaivaasal project elevation & completed photos
│   ├── varatharajapuram-*.jpg # Varatharajapuram project completed photos
│   ├── elevation-*.jpg   # 4K Architectural elevations & night illumination renders
│   └── rooftop-garden.jpg# Terrace garden installation
└── assets/               # Source client catalogs & original PDF blueprints
```

---

## How to Preview Locally
Simply double-click `index.html` or any page (`about.html`, `services.html`, `projects.html`, `packages.html`, `contact.html`) in any modern web browser.

---

## Deployment Instructions
Because this website is built with static HTML5 and CSS3, it can be deployed to any static host:
1. **GitHub Pages:** Commit repository and enable Pages in repository settings.
2. **Netlify:** Drag and drop the project folder into Netlify Drop.
3. **Vercel / Cloudflare Pages:** Connect repository and set root directory to `/`.
4. **Apache / Nginx Web Server:** Copy files directly into `/var/www/html/` or `public_html/`.
