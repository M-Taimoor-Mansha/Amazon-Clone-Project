# 🛒 Amazon Clone Project

A responsive, Amazon-inspired e-commerce homepage built with **HTML5, CSS3, Tailwind CSS, and Vanilla JavaScript**.

This project recreates the look and feel of an online marketplace homepage, including a two-level navigation header, search interface, promotional hero slider, shopping and category sections, horizontally scrollable product collections, product imagery, ratings, pricing, and a multi-column footer.

The repository is a front-end learning project. It demonstrates page layout, responsive styling, reusable CSS patterns, and basic JavaScript interactions without requiring a framework, backend, database, or build system.

> **Disclaimer:** This is an independent educational and portfolio project. It is not affiliated with, endorsed by, sponsored by, or officially connected to Amazon. Amazon names, logos, product imagery, and other referenced materials belong to their respective owners.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-38B2AC?style=flat&logo=tailwindcss&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

---

## Table of Contents

- [Overview](#overview)
- [Project Information](#project-information)
- [Features](#features)
- [Homepage Sections](#homepage-sections)
- [Interactive Functionality](#interactive-functionality)
- [Technology Stack](#technology-stack)
- [Project Architecture](#project-architecture)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Design System](#design-system)
- [Responsive Design](#responsive-design)
- [External Resources](#external-resources)
- [Customization](#customization)
- [Deployment](#deployment)
- [Current Scope and Limitations](#current-scope-and-limitations)
- [Potential Future Improvements](#potential-future-improvements)
- [Troubleshooting](#troubleshooting)
- [License](#license)
- [Author](#author)

---

## Overview

The Amazon Clone Project is a static e-commerce homepage inspired by the Amazon India shopping experience.

The page brings together common marketplace interface patterns, including:

- A dark two-level navigation header.
- A location and delivery indicator.
- A prominent search bar.
- Account, orders, and cart navigation areas.
- A large promotional image slider.
- Category and shopping recommendation cards.
- Horizontal product and deal collections.
- Product information with sample prices and ratings.
- A structured footer with informational links.

The implementation uses native HTML, CSS, and JavaScript, with Tailwind CSS utilities for much of the page layout and responsive behavior.

There is no real product catalog, account system, checkout flow, or order processing service connected to the project. The product content is static demonstration content embedded in the HTML.

## Project Information

| Property | Details |
|---|---|
| Project name | Amazon Clone Project |
| Repository | [Amazon-Clone-Project](https://github.com/M-Taimoor-Mansha/Amazon-Clone-Project) |
| Project type | E-commerce homepage UI clone |
| Architecture | Static front-end website |
| Markup | HTML5 |
| Styling | CSS3 and Tailwind CSS |
| Programming language | Vanilla JavaScript |
| Icons | Font Awesome 6.5.1 |
| Typography | Google Fonts, Plus Jakarta Sans and Outfit |
| Backend | Not included |
| Database | Not included |
| Package manager | Not required |
| Build system | Not required |
| License | MIT |

---

## Features

### Homepage and navigation

- Amazon-inspired top navigation bar.
- Secondary category navigation bar.
- Brand logo image.
- Delivery location display.
- Search input with category selector styling.
- Search icon and decorative AI-style icon.
- Account and Lists area.
- Returns and Orders area.
- Shopping cart presentation.
- Responsive visibility for selected navigation links.

### Promotional content

- Large promotional hero banner.
- Multiple promotional slides.
- Previous and next slider controls.
- Automatic slide rotation.
- Five-second slide interval.
- Smooth CSS transitions for slide visibility.
- Shopping and promotional recommendation cards.

### Shopping collections

- Today's Deals horizontal product collection.
- Sustainable Finds image collection.
- Electronics clearance collection.
- Products inspired by browsing history.
- Best Sellers in Books collection.
- Product images, sample prices, discount labels, and rating displays.

### Layout and presentation

- Responsive product and category grids.
- Horizontally scrollable product rows.
- Card-based content sections.
- Image-focused promotional layouts.
- Amazon-inspired navy, blue, yellow, and orange palette.
- Hover and transition effects.
- Responsive footer layout.
- Back to Top interaction.

### Lightweight implementation

- No front-end framework required.
- No package installation required.
- No database or backend required.
- Static files can be served from any basic web server.
- JavaScript is used for the hero slider and Back to Top behavior.

---

## Homepage Sections

The current repository contains a single main page, `index.html`. Its content is organized into the following sections.

### 1. Top Navigation Header

The top header uses a dark navy background inspired by Amazon's familiar navigation design.

It contains:

- Logo image linking to the page's top.
- Delivery location information.
- Search interface.
- Account and Lists presentation.
- Returns and Orders presentation.
- Shopping cart icon and label.

The delivery label currently displays **Lahore, 44000** as static text. It is not connected to a location service or delivery-address selector.

### 2. Secondary Navigation

A second navigation row uses a darker blue-gray background and displays marketplace-style links such as:

- All
- Fresh
- Amazon miniTV
- Sell
- Best Sellers
- Mobiles
- Today's Deals
- Electronics
- Prime
- Gift Ideas

Some links are hidden at smaller responsive breakpoints to preserve horizontal space.

These are presentation links and are not connected to separate category pages.

### 3. Promotional Hero Slider

The hero area displays a sequence of large promotional images.

The current HTML contains three slides. The JavaScript controls which slide has the `active` class.

**Controls:**

- Previous button.
- Next button.
- Automatic slide transition every five seconds.

The slider is intended to provide a prominent promotional area above the shopping content.

The images are loaded from externally hosted Amazon image URLs, so their availability is dependent on those external resources.

### 4. Shopping and Recommendation Cards

A responsive four-column section presents several promotional cards:

- Amazon Prime promotional content.
- Women's fashion categories.
- Home appliances.
- Sign-in recommendation.
- An additional promotional image.

The grid changes its column count based on the available screen width.

### 5. Today's Deals

This section presents a horizontal collection of product and deal cards.

Examples of the displayed content include:

- Computer and accessory deals.
- HP laptop promotion.
- OnePlus Nord 4 promotion.
- boAt headphone deals.
- Luggage and backpack offers.
- Fashion products.

Each item includes product imagery and a promotional label such as a discount, deal of the day, or starting price.

The row uses horizontal overflow scrolling rather than a JavaScript-powered product carousel.

### 6. Sustainable Finds

A horizontally scrollable image collection presents products under the heading **Shop our sustainable finds**.

The current section is image-focused and does not implement product filtering or product detail navigation.

### 7. Electronics Clearance

A responsive grid displays electronics product images under a promotional clearance heading.

The layout expands to multiple columns on wider screens and reduces the number of columns on smaller screens.

### 8. Inspired by Your Browsing History

This section displays product-style cards with:

- Product image.
- Product name.
- Star rating.
- Review-count text.
- Sample price in Indian Rupees (₹).

The displayed browsing-history content is static sample content. It is not generated from actual visitor browsing activity.

### 9. Best Sellers in Books

The book collection displays a horizontal row of book-cover images.

It is a visual product showcase and does not connect to a live book catalog or shopping service.

### 10. Footer

The footer includes:

- Personalized recommendation prompt.
- Sign-in presentation button.
- New customer link.
- Back to Top control.
- Informational link groups.
- Social and company-related navigation content.

The Back to Top area is connected to JavaScript and smoothly scrolls the page to the top.

---

## Interactive Functionality

The current JavaScript is contained in `script.js`.

It initializes after the HTML document has loaded.

### JavaScript initialization

The main implementation listens for the `DOMContentLoaded` event before selecting page elements and attaching event handlers.

### Hero slider

The slider uses the following elements:

| Element | Purpose |
|---|---|
| `.slide` | Identifies each slide |
| `#prevBtn` | Moves to the previous slide |
| `#nextBtn` | Moves to the next slide |
| `.active` | Identifies the currently visible slide |

The JavaScript maintains a current slide index.

The next-slide calculation wraps around to the first slide when the end is reached. The previous-slide calculation wraps around to the final slide when moving backward from the first slide.

The automatic slideshow uses `setInterval()` with a five-second interval.

When a visitor clicks either navigation button, the current interval is stopped and restarted. This resets the automatic rotation interval after manual navigation.

Simplified flow:

```text
Page loads
    |
    v
Find slides and navigation buttons
    |
    v
Set current slide to index 0
    |
    v
Display active slide
    |
    v
Start five-second interval
    |
    +-----------------------------+
    |                             |
    v                             v
Next button                   Previous button
    |                             |
    v                             v
Increment index                Decrement index
    |                             |
    +--------------+--------------+
                   |
                   v
          Update active slide
                   |
                   v
        Restart automatic timer
```

### Back to Top

The footer contains an element with the ID `backToTopBtn`.

When clicked, the script calls:

```javascript
window.scrollTo({
  top: 0,
  behavior: 'smooth',
});
```

This smoothly scrolls the visitor to the top of the page.

### Important distinction: styled components versus active functionality

The stylesheet contains additional component styles for a more extensive e-commerce interface, including search suggestions, product cards, wishlist buttons, quick-view modals, cart drawers, toast notifications, and theme variables.

However, the current `script.js` only wires up the hero slider and Back to Top interaction. The presence of CSS styles for other components does not mean those components are fully implemented or interactive in the current homepage.

Likewise, the search field, account links, category links, product links, sign-in buttons, and cart presentation should be treated as interface elements rather than complete shopping workflows.

---

## Technology Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic page structure and content |
| CSS3 | Custom styles, design tokens, transitions, and responsive rules |
| Tailwind CSS | Utility classes for layout, spacing, colors, grids, and breakpoints |
| Vanilla JavaScript (ES6+) | Hero slider and Back to Top interaction |
| Font Awesome 6.5.1 | Navigation and interface icons |
| Google Fonts | Plus Jakarta Sans and Outfit typography |
| DOM API | Selecting elements and registering click handlers |

### HTML5

The page uses HTML for the navigation, promotional sections, product collections, images, buttons, and footer.

### CSS3

The custom stylesheet provides design tokens, base styles, component styling, hover effects, transitions, responsive adjustments, and a reduced-motion media query.

### Tailwind CSS

Tailwind CSS is loaded through the CDN script in `index.html`:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

It is used extensively for layout, responsive grids, spacing, typography, background colors, and utility styling.

### Font Awesome

The page loads Font Awesome 6.5.1 from cdnjs:

```html
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
/>
```

### Google Fonts

The custom stylesheet imports:

- **Plus Jakarta Sans:** Main interface and body typography.
- **Outfit:** Display and heading typography.

---

## Project Architecture

The project follows a simple static front-end architecture.

```text
                 Visitor's Browser
                         |
                         v
                     index.html
                         |
              +----------+----------+
              |                     |
              v                     v
          styles.css             script.js
              |                     |
              v                     v
      Visual presentation     DOM interactions
              |                     |
              |             +-------+-------+
              |             |               |
              |             v               v
              |        Hero slider      Back to Top
              |             |               |
              +-------------+---------------+
                            |
                            v
                   Rendered Homepage
```

There is no server-side application layer. The browser loads the HTML, CSS, JavaScript, and external visual resources directly.

---

## Project Structure

The current repository uses a simple root-level structure:

```text
Amazon-Clone-Project/
│
├── index.html       # Main e-commerce homepage
├── styles.css       # Custom design system and component styles
├── script.js        # Hero slider and Back to Top functionality
├── LICENSE          # MIT License
└── README.md        # Project documentation
```

### File descriptions

| File | Responsibility |
|---|---|
| `index.html` | Contains the complete homepage markup and content sections |
| `styles.css` | Defines CSS variables, typography, component styling, transitions, and responsive rules |
| `script.js` | Implements the promotional hero slider and Back to Top interaction |
| `LICENSE` | Contains the MIT License |
| `README.md` | Documents the project and explains how to run it |

The current implementation does not require separate `css/`, `js/`, or `assets/` directories. Product and promotional images are referenced using external URLs in the HTML.

---

## Getting Started

### Requirements

- A modern web browser.
- An internet connection for Tailwind CSS, Font Awesome, Google Fonts, and externally hosted images.
- Git (optional).
- Visual Studio Code or another code editor (optional).

No Node.js installation, npm packages, framework setup, database, or build command is required.

### 1. Clone the repository

Open a terminal and run:

```bash
git clone https://github.com/M-Taimoor-Mansha/Amazon-Clone-Project.git
```

### 2. Navigate to the project directory

```bash
cd Amazon-Clone-Project
```

### 3. Run the website

**Option A: Open directly**

Open `index.html` in your preferred web browser.

**Option B: Visual Studio Code Live Server**

1. Open the cloned project folder in Visual Studio Code.
2. Install the Live Server extension if necessary.
3. Open `index.html`.
4. Right-click inside the editor.
5. Select **Open with Live Server**.

**Option C: Python local server**

If Python is installed, run:

```bash
python -m http.server 5500
```

Then visit:

```text
http://localhost:5500
```

Python is only used here as a simple static file server. The project itself is not a Python application.

---

## How to Use

1. Open the homepage in a browser.
2. Explore the top navigation and marketplace-style category bar.
3. Use the previous and next arrows to navigate the promotional hero slides.
4. Allow the hero slider to rotate automatically every five seconds.
5. Scroll through the shopping cards and promotional collections.
6. Horizontally scroll the product rows to view additional items.
7. Explore the product names, sample prices, ratings, and promotional labels.
8. Use the Back to Top control in the footer to return to the beginning of the page.

Search, cart, sign-in, and product navigation are currently visual interface elements and do not complete real transactions.

---

## Design System

The design is inspired by the Amazon India homepage, using a recognizable marketplace color palette and familiar shopping layout patterns.

### Brand-inspired color palette

The stylesheet defines reusable CSS custom properties.

| Token | Value | Purpose |
|---|---|---|
| `--amazon-navy` | `#131921` | Main navigation background |
| `--amazon-dark-blue` | `#232F3E` | Secondary navigation and footer |
| `--amazon-light-blue` | `#37475A` | Supporting navigation surfaces |
| `--amazon-gold` | `#FF9900` | Primary orange accent |
| `--amazon-yellow` | `#FFD814` | Highlight and action accent |
| `--amazon-yellow-hover` | `#F7CA00` | Hover state for yellow elements |
| `--amazon-accent` | `#008296` | Supporting accent |
| `--amazon-teal` | `#00A896` | Additional accent |
| `--bg-primary` | `#F3F4F6` | Default page background |
| `--bg-surface` | `#FFFFFF` | Card and surface background |
| `--text-main` | `#0F172A` | Main text |
| `--text-muted` | `#64748B` | Secondary text |

### Typography

The stylesheet imports Plus Jakarta Sans and Outfit from Google Fonts.

These fonts provide a modern sans-serif appearance suitable for a product-focused shopping interface.

### Component styling

The stylesheet includes reusable styles for:

- Navigation link borders.
- Search containers and suggestion dropdowns.
- Mobile navigation drawer.
- Hero slider and slide controls.
- Category filter pills.
- Product cards and image wrappers.
- Wishlist button appearance.
- Quick-view modal appearance.
- Cart drawer appearance.
- Quantity controls.
- Toast notifications.
- Responsive layout adjustments.

Some of these component styles are design foundations for possible future functionality and are not currently connected to interactive JavaScript behavior.

### Dark theme styles

The stylesheet includes a `[data-theme="dark"]` CSS variable override.

This defines alternate surface, text, border, and shadow colors. The current JavaScript does not provide a theme toggle, so dark mode is not an active user-facing feature in the current implementation.

---

## Responsive Design

The page combines Tailwind responsive utilities with custom CSS media queries.

### Responsive behavior

| Area | Responsive behavior |
|---|---|
| Top navigation | Selected delivery and navigation elements are hidden on smaller screens |
| Secondary navigation | Some category links appear only at medium or large breakpoints |
| Hero section | Banner height and controls adapt to viewport width |
| Shopping cards | Grid changes from one column to two and then four columns |
| Electronics section | Grid expands from one column to as many as five columns |
| Product collections | Horizontal overflow allows touch and pointer scrolling |
| Footer | Two columns on small screens and four columns on wider screens |
| Hero typography | Heading size reduces on narrow screens |

### Custom breakpoints

The stylesheet includes responsive rules at:

- 1024px.
- 768px.
- 640px for hero title sizing.

Tailwind's responsive utilities are also used throughout the HTML.

### Reduced motion

The stylesheet includes a `prefers-reduced-motion: reduce` media query that minimizes animation and transition durations for visitors who request reduced motion in their operating system or browser settings.

---

## External Resources

The project loads several resources from external services.

| Resource | Purpose |
|---|---|
| Tailwind CSS CDN | Utility-first styling |
| cdnjs Font Awesome 6.5.1 | Navigation and interface icons |
| Google Fonts | Plus Jakarta Sans and Outfit typography |
| Amazon-hosted image URLs | Product and promotional imagery |
| pngimg.com | Logo image source |

### External image dependency

The current HTML references images hosted on Amazon's image delivery domains and other external image hosts.

These images are not stored locally in the repository. They may change, become unavailable, or be subject to external hosting restrictions.

For a more reliable deployment, consider using appropriately licensed images stored in the repository or from a stable image provider.

---

## Customization

### Change the logo

Locate the logo image in the top navigation of `index.html` and replace its `src` with an image you are authorized to use.

### Change the delivery location

Find the static delivery text in `index.html`:

```html
<p class="text-sm font-bold">Lahore, 44000</p>
```

Replace it with the desired display text.

### Change the hero images

Find the elements with the `.slide` class in `index.html`.

Replace each slide's image URL with a suitable image. To add another slide, duplicate a slide block and ensure it uses the same `.slide` class.

The existing JavaScript automatically includes all elements matching that class.

### Change the automatic slider interval

Open `script.js` and locate:

```javascript
slideInterval = setInterval(nextSlide, 5000);
```

Change `5000` to the desired interval in milliseconds. For example, `7000` represents seven seconds.

### Change product content

Product collections are written directly in `index.html`.

Update the relevant image URLs, names, promotional labels, prices, and rating text.

The current page does not retrieve this information from a product API or database.

### Change colors

Open `styles.css` and modify the custom properties inside the `:root` selector.

For example:

```css
:root {
  --amazon-navy: #131921;
  --amazon-dark-blue: #232F3E;
  --amazon-gold: #FF9900;
  --amazon-yellow: #FFD814;
}
```

Some colors are also written directly as Tailwind utility classes in `index.html`, so update those classes if you want to change every color consistently.

### Change typography

The Google Fonts import is near the top of `styles.css`. Replace or modify the imported font families and update the `font-family` declarations as needed.

### Add another product collection

Duplicate one of the existing section structures in `index.html`, update its heading and product items, and choose the appropriate Tailwind grid or horizontal scrolling layout.

---

## Deployment

This is a static website. It can be hosted on any platform that serves HTML, CSS, and JavaScript files.

### GitHub Pages

1. Open the repository on GitHub.
2. Navigate to **Settings**.
3. Select **Pages**.
4. Choose the `main` branch.
5. Select the repository root directory.
6. Save the configuration.
7. Wait for GitHub Pages to publish the site.

### Vercel

1. Sign in to Vercel.
2. Import the GitHub repository.
3. Select the repository root as the project directory.
4. No build command is required for the current static implementation.
5. Deploy the website.

### Netlify

1. Import the GitHub repository.
2. Set the publish directory to the repository root.
3. Leave the build command empty.
4. Deploy the website.

### Deployment checklist

Before publishing, verify that:

- `index.html`, `styles.css`, and `script.js` are present.
- The stylesheet and JavaScript paths are correct.
- The hero slider controls work.
- The Back to Top control works.
- External images load successfully.
- Tailwind CSS and Font Awesome load successfully.
- Google Fonts are available.
- Product rows can be scrolled horizontally on touch devices.
- The layout works at mobile, tablet, and desktop widths.
- The project disclaimer is visible and accurate.

---

## Current Scope and Limitations

This repository currently implements a static e-commerce homepage, not a complete online shopping platform.

| Feature | Current status |
|---|---|
| Amazon-inspired homepage | Implemented |
| Two-level navigation UI | Implemented visually |
| Delivery location display | Static text |
| Search field | UI only, no search logic |
| Category selector | UI only |
| Account and Lists | UI only |
| Returns and Orders | UI only |
| Cart presentation | UI only |
| Promotional hero slider | Implemented |
| Automatic slide rotation | Implemented |
| Previous and next slider controls | Implemented |
| Shopping recommendation cards | Static content |
| Today's Deals collection | Static content with horizontal scrolling |
| Sustainable Finds collection | Static images with horizontal scrolling |
| Electronics collection | Static image grid |
| Browsing-history recommendations | Static sample content |
| Book collection | Static images with horizontal scrolling |
| Product ratings and prices | Static sample text |
| Back to Top | Implemented |
| Responsive layout | Implemented through Tailwind and CSS |
| Product search functionality | Not implemented |
| Product filtering and sorting | Not implemented |
| Product detail pages | Not implemented |
| Functional wishlist | Not implemented |
| Functional shopping cart | Not implemented |
| Quantity management | Not implemented |
| Checkout process | Not implemented |
| Payment integration | Not implemented |
| User authentication | Not implemented |
| Order history | Not implemented |
| Backend or database | Not included |
| Live product API | Not included |
| Functional dark-mode toggle | Not implemented |
| Persistent user preferences | Not implemented |

### Important project notes

**No real purchases:** The page does not process orders, payments, or transactions.

**No real accounts:** Sign-in and account-related elements are visual placeholders.

**No live inventory:** Product names, prices, ratings, and discounts are static content and should not be interpreted as current offers.

**No real cart:** The cart is represented in the navigation UI but does not currently manage products.

**External images:** Product and banner images depend on third-party image URLs and may not always load.

**Additional CSS components:** Some advanced component styles exist in the stylesheet, but their corresponding interactive features are not implemented in the current JavaScript.

---

## Potential Future Improvements

The following are ideas for extending the current front-end project. They are not included in the current implementation.

### Shopping experience

- Implement functional product search.
- Add live search suggestions.
- Add category-based navigation.
- Implement product filtering and sorting.
- Add product detail views.
- Add product quick-view modal behavior.
- Add product comparison.
- Add pagination or load-more functionality.

### Cart and wishlist

- Implement add-to-cart functionality.
- Add quantity controls.
- Calculate subtotal and total.
- Persist cart contents using LocalStorage.
- Implement wishlist interactions.
- Add cart and wishlist item counters.
- Provide clear empty-cart and empty-wishlist states.

### User experience

- Add a functional mobile navigation drawer.
- Add accessible keyboard controls for the hero slider.
- Pause automatic slider rotation when the visitor interacts with it.
- Add a working dark-mode toggle.
- Improve loading and error states for images.
- Add product skeleton loading where appropriate.
- Improve accessibility labels and keyboard navigation.

### Backend and data

- Connect to a product API.
- Create a centralized product catalog.
- Add user authentication.
- Store customer accounts securely.
- Add order history.
- Implement checkout and payment integration through a suitable provider.
- Add server-side order validation.
- Build an administration interface for products and inventory.

### Engineering improvements

- Separate HTML, CSS, and JavaScript into dedicated folders.
- Move static product data into structured JSON.
- Build reusable product-rendering functions.
- Add automated tests.
- Optimize and locally host appropriately licensed images.
- Add SEO metadata and social sharing metadata.
- Improve performance and accessibility audits.

---

## Troubleshooting

### The page appears without styling

Check that `styles.css` is in the repository root and that `index.html` references it correctly:

```html
<link rel="stylesheet" href="styles.css">
```

Also verify that Tailwind CSS CDN is accessible.

### Icons are missing

The project loads Font Awesome from cdnjs. Check your internet connection and verify that the Font Awesome stylesheet loads successfully.

### Product or hero images do not load

The current image URLs are hosted externally. An image may be unavailable or restricted by its provider. Replace the affected URL with a working image source you are authorized to use.

### The hero slider does not move

Check that:

- The HTML contains elements with the `.slide` class.
- The previous button has the ID `prevBtn`.
- The next button has the ID `nextBtn`.
- `script.js` is included in `index.html`.
- The browser console does not report JavaScript errors.

### The Back to Top control does not work

Check that the footer element has the ID `backToTopBtn` and that `script.js` loads successfully.

### The page is difficult to use on a small screen

Check the viewport meta tag in `index.html`:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Also verify that Tailwind CSS and the custom responsive stylesheet are loading.

### The layout looks different without internet access

Tailwind CSS, Font Awesome, Google Fonts, and many product images are loaded externally. Without an internet connection, some styling resources, icons, fonts, and images may be unavailable.

---

## License

This project is licensed under the **MIT License**.

Copyright (c) 2026 CodewithTaimoor.

You may use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, subject to the conditions of the MIT License.

See the [LICENSE](LICENSE) file for the complete license text.

---

## Author

**Muhammad Taimoor Mansha**

- GitHub: [@M-Taimoor-Mansha](https://github.com/M-Taimoor-Mansha)
- LinkedIn: [Muhammad Taimoor Mansha](https://linkedin.com/in/muhammad-taimoor-mansha-a09455228)
- Portfolio: [Personal Portfolio](https://m-taimoor-mansha.github.io/Portfolio/)

---

<p align="center">
  Built with HTML5, CSS3, Tailwind CSS, and Vanilla JavaScript.
  <br><br>
  <strong>Amazon Clone Project</strong>
  <br>
  An educational e-commerce homepage interface.
</p>
