# QA Manual Portfolio — Dimas Nurindra

Portfolio website for a **Quality Assurance Manual Specialist**, highlighting expertise in end-to-end manual testing, API testing, regression cycles, and fintech application validation.

## Live Demo

[View Live Portfolio](https://portfolio-dimas.my.id/)

---

## Features

- **Scroll Reveal Animations** — Sections and cards animate into view as you scroll using Intersection Observer
- **Dark / Light Mode** — Theme toggle with `localStorage` persistence and system preference detection
- **Responsive Design** — Mobile-first layout built with Tailwind CSS
- **Tool Marquee** — Dual-row animated carousel showing testing tools and skills
- **Agile QA Process** — Visual step-by-step breakdown of the iterative SDLC
- **Project Showcase** — Work samples and project cards with live dashboard integration
- **Certifications** — Verified credentials from MySkill and Digital Talent Scholarship
- **Contact Form** — Serverless form handling via Formspree

---

## Built With

- **HTML5** — Semantic markup for SEO and accessibility
- **Tailwind CSS** (CDN) — Custom design system with premium color palette
- **Vanilla JavaScript** — Intersection Observer, theme toggle, form handling
- **Google Fonts (Inter)** — Modern, readable typography
- **Material Symbols** — Consistent iconography
- **Formspree** — Serverless form submission

---

## Project Structure

```text
├── index.html               # Main landing page
├── projects.html            # All projects page
├── src/
│   ├── components/          # Reusable UI components
│   ├── css/
│   │   └── styles.css       # Custom animations, dark mode, design tokens
│   └── assets/
│       ├── fonts/           # Local font files
│       ├── icons/           # Standalone icon assets
│       └── images/
│           ├── icons/       # Tool & technology icon images
│           ├── logos/       # Certification brand logos
│           └── projects/    # Project screenshots
└── README.md                # Documentation
```

---

## Setup

1. **Clone the repo**:
   ```bash
   git clone https://github.com/DimasIndraa1/portfolio-Qa.git
   ```

2. **Open locally**:
   Open `index.html` in any browser. No build step required.

3. **Customize contact form**:
   Replace the Formspree endpoint in `index.html` with your own form ID.
