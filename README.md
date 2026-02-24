# The Collector Bitcoin

> A product landing page for "The Collector Bitcoin," a luxury commemorative physical Bitcoin souvenir coin with Shopify e-commerce integration.

![Status](https://img.shields.io/badge/status-archived-lightgrey)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Live Demo

[https://izzydoesizzy.github.io/bitcoin](https://izzydoesizzy.github.io/bitcoin)

## Overview

This is the product landing page for "The Collector Bitcoin" -- a luxury physical souvenir coin designed for Bitcoin enthusiasts, investors, and crypto nerds. The site showcases the coin's features (materials, size, weight), displays Bitcoin market facts, and integrates a Shopify Buy Button for direct purchasing. A prominent disclaimer clarifies that the collectible does not hold actual Bitcoin value. The coin is crafted from a premium blend of iron, brass, copper, and zinc alloy.

## Features

- Hero section with animated coin image (bounceInRight via WOW.js) and call-to-action "GET IT NOW" button
- Spinning coin GIF animation in the features section
- Product details: materials (iron, brass, copper, zinc alloy), dimensions (38mm diameter, 3mm thickness, 30g weight)
- Bitcoin market facts counter section (total market cap, circulating supply, current value)
- Shopify Buy Button embedded e-commerce integration with add-to-cart and checkout flow
- Responsive navigation with fixed-top navbar (Home, About, Order)
- Preloader wave animation on page load
- Google Analytics tracking
- Bootstrap grid layout with responsive design
- Social meta tags for Facebook, Twitter, and Google sharing

## Screenshots

<!-- ![Screenshot](screenshot.png) -->

## Tech Stack

- HTML5
- CSS3 (Bootstrap 3, custom styles, responsive breakpoints)
- jQuery 1.12
- Shopify Buy Button SDK (e-commerce)
- WOW.js (scroll animations)
- Slick / Swiper (slider support)
- Modernizr
- Google Analytics
- Hosted on GitHub Pages

## Getting Started

### Run Locally

No build step required:

1. **Clone the repository**
   ```bash
   git clone https://github.com/izzydoesizzy/bitcoin.git
   cd bitcoin
   ```

2. **Open in browser**
   ```bash
   open index.html
   # or use a local server:
   npx serve .
   ```

### Deploy to GitHub Pages

1. Push to the `gh-pages` branch
2. Go to Settings > Pages > Source: Deploy from branch
3. Site live at `https://izzydoesizzy.github.io/bitcoin`

## Project Structure

```
bitcoin/
├── index.html              # Main product landing page
├── index2.html             # Alternate layout version
├── indexNEW.html           # Updated layout version
├── archive.html            # Archived page
├── style.css               # Primary stylesheet
├── custom.css              # Custom style overrides
├── css/
│   ├── bootstrap.min.css   # Bootstrap framework
│   ├── elements.css        # UI element styles
│   ├── color-variation.css # Color scheme
│   └── responsive.css      # Responsive breakpoints
├── js/
│   ├── main.js             # Main application logic
│   ├── bootstrap.min.js    # Bootstrap JS
│   ├── slick.min.js        # Slider plugin
│   ├── plugins.js          # Additional plugins
│   └── vendor/             # Modernizr, jQuery
├── img/                    # Product images, icons, coin GIF
├── fonts/                  # Custom web fonts
├── php/                    # Server-side utilities
├── Documentation/          # Theme documentation
└── favicon.ico             # Site favicon
```

## Tags

`fun-project` `documentation`

## Created

2017-11

## Status

Legacy -- Built during the 2017 cryptocurrency boom as a novelty product site.

## Author

**Izzy Piyale-Sheard** -- [@izzydoesizzy](https://github.com/izzydoesizzy)
