Sterling Wealth Advisors — Investment Strategy Landing Page

A modern, single-page landing site for an investment strategy consultancy, built to generate qualified leads through an enquiry form and a free lead-magnet checklist offer.

Live site: https://yustal-perp.github.io/Finance-Guru/ (enable GitHub Pages to activate this link — see below)

## Tech Stack

Plain HTML5, CSS3, and vanilla JavaScript — no frameworks, no build step, no dependencies. Everything lives in a single [`index.html`](index.html) file.

## Features

- Sticky navigation bar with mobile hamburger menu
- Full-viewport hero section with fade-in animation and smooth scrolling
- Six-card "Why Choose Us" benefits grid with hover effects
- Four-step investment process timeline (horizontal on desktop, stacked on mobile)
- Testimonials grid with star ratings
- Lead-magnet banner (free checklist offer) linking to the enquiry form
- Enquiry form with client-side validation (name, email, phone) submitting via [FormSubmit](https://formsubmit.co/)
- Accordion FAQ section
- Final call-to-action banner and footer with disclaimer
- Fully responsive (mobile, tablet, desktop) using Flexbox, Grid, and media queries

## Running Locally

No build tools required. Either open the file directly in a browser:

```bash
open index.html
```

or serve it locally:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Enabling GitHub Pages (optional)

Repo → Settings → Pages → Deploy from branch → `main` / root. The site will then be published at `https://yustal-perp.github.io/Finance-Guru/`.

## Enquiry Form Setup

The form posts to [FormSubmit](https://formsubmit.co/) at the address configured in `index.html`. On the **first** submission, FormSubmit sends a confirmation email to that address — it must be approved before subsequent submissions are delivered.

## Disclaimer

This site is a template for informational/marketing purposes only and does not constitute financial advice.
