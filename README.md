# Maxwynn Website

A freelance website for **Maxwynn**, a creator media agency that connects brands with content creators through campaign strategy, content production, and creator distribution.

**Live site:** https://www.maxwynn.eu/

## Overview

A static, single-page marketing site with separate Privacy Notice and Terms of Service pages. It is built with plain HTML, CSS, and JavaScript, with no frameworks and no build step, and is deployed on GitHub Pages.

## Sections

| Section | What it shows |
| --- | --- |
| Home | Hero with an animated particle-network background and a brand, creator, and Maxwynn match diagram |
| Services | Brand Strategy, Content Production, and Creator Distribution cards |
| Process | "The Maxwynn Engine", a three-step pipeline: The Brand, Maxwynn, Creator Audience |
| About | Agency overview |
| Contact | Call-to-action section |
| Privacy Notice and Terms of Service | Separate legal pages (`privacy.html`, `terms.html`) |

## Features

- Responsive layout with breakpoints for desktop, tablet, and mobile, plus a mobile burger menu
- Light and dark theme toggle, with the choice saved in `localStorage`
- Animated hero canvas (particle network) that reacts to mouse movement
- Scroll-reveal animations using `IntersectionObserver`
- Animated process diagram
- Smooth in-page navigation with an offset for the fixed header
- Sticky navigation bar that changes style on scroll

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, grid, media queries)
- Vanilla JavaScript (ES6)
- Google Fonts: Sora and DM Sans

## Project Structure

```
Maxwynn-main/
├── index.html      # Home page (all main sections)
├── privacy.html    # Privacy Notice
├── terms.html      # Terms of Service
├── style.css       # Styles for the main page
├── script.js       # Navigation, theme toggle, animations, hero canvas
└── image/
    ├── logo_maxwynn.png
    └── logo_maxwynn.ico
```

## Run Locally

No installation is needed. Open `index.html` in a browser, or serve the folder locally:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy on GitHub Pages

1. Push the files to a GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.

## My Role

Web developer: built and deployed the site.

## Notes

- Shared in this portfolio with the client's permission.
- Client contact details were removed from this copy. The email address in the contact button and legal pages is a placeholder (`contact@example.com`), so replace it before reusing the site.
- The privacy and terms text is sample content and is not legal advice.
