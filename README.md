# Mardass – WooCommerce Store

A fashion e-commerce website built with WordPress and WooCommerce.

---

## Project Status

🚧 In Progress

---

## Overview

This project documents the process of building and configuring a WooCommerce online store, focusing on security, structure, and practical implementation.

---

## Completed So Far

- Clean WordPress installation
- WooCommerce setup
- Security configuration with Wordfence (brute force protection, 2FA, firewall rules, CAPTCHA enabled)
- Structured product data architecture (SKU system, category structure, variable product logic)
- CSV-based product import
- SEO-oriented product naming strategy
- Stock management per variation

---

## 🛍️ Single Product Page Customization

The default WooCommerce product gallery layout was redesigned using pure CSS (Flexbox), without modifying any PHP files.

Key improvements:

- Repositioned product thumbnails to the side of the main image (desktop & tablet)
- Implemented a flexible layout using `display: flex`
- Improved visual hierarchy between main image and gallery thumbnails
- Added hover effects (opacity and scale) for better user interaction
- Optimized spacing and alignment for a cleaner UI

Responsive adjustments:

- On mobile devices, the layout switches to a vertical structure
- Thumbnails are displayed horizontally with proper spacing
- Ensured full responsiveness across different breakpoints

---

## 🛍️ Shop Page Customization

The default shop layout was extended by adding a fully functional sidebar with product filtering capabilities.

Key improvements:

- Added a custom WooCommerce sidebar using widgets
- Integrated product filters including price range, size, color, and category
- Implemented product search functionality within the shop sidebar
- Enabled sidebar layout through theme customization (Astra Product Catalog settings)
- Converted the shop page from a full-width layout to a structured sidebar layout

Responsive adjustments:

- On mobile devices, filters are displayed in a compact, toggle-based interface for better usability
- Optimized layout and spacing for smaller screens
- Maintained accessibility of filtering options without cluttering the UI

---

## 🏠 Homepage Customization

The homepage was fully redesigned with a focus on branding, performance, and responsive user experience.

Hero section:

- Implemented a video-based hero section for desktop and tablet devices to create a strong visual impact
- Created a separate hero section specifically for mobile devices using a static image
- Used responsive visibility settings to hide the video version on mobile and display the image version instead

New Arrivals (product showcase):

- Designed a custom product showcase section instead of using default WooCommerce layouts
- Implemented interactive product cards using Essential Addons (Flip Box)

Desktop & Tablet behavior:
- Front side displays product image and title
- Back side (on hover) shows alternate image, product description, and a "View Product" button

Mobile behavior:
- Created a separate mobile version of the section with a hover-independent design
- Used responsive visibility controls to hide the desktop version and display the mobile version instead
- Ensured all product information and actions are always visible
- Adjusted layout to a 2-column grid for better usability on smaller screens

Layout & design:

- Built multiple custom sections, including:
  - New Arrivals
  - Best Seller promotional section
  - Brand philosophy section
  - Customer testimonials
- Designed all sections manually using Elementor for full layout control

Responsive strategy:

- Used device-specific sections (show/hide) to handle major layout differences
- Customized grid behavior across breakpoints (including 2-column mobile layout)
- Optimized spacing, stacking, and readability for different screen sizes

Design approach:

- Focused on a clean, minimal UI aligned with a fashion brand identity
- Maintained visual consistency across all sections
- Balanced imagery, typography, and whitespace for a modern e-commerce experience

---

## 🛒 Cart & Checkout Experience

To improve the shopping flow, a slide-out cart (off-canvas mini cart) was implemented instead of the default WooCommerce cart page.

### Implementation

- Used **Modern Cart for WooCommerce**
- Maintained plugin structure for stability
- Customized UI using CSS (typography, spacing, width)

### Improvements

- Instant cart access without page reload
- Smooth slide-out interaction
- Optimized layout for better readability
- Direct access to checkout from cart

### Checkout Page

- Customized WooCommerce checkout layout
- Improved form structure and readability
- Integrated multiple payment methods (PayPal & Stripe)

---

## 💳 Payment Integration

Integrated secure payment gateways using:

- **Stripe (Credit/Debit Cards)**
- **PayPal**

### Implementation Details

- Configured using official WooCommerce plugins (Payment Plugins for Stripe & PayPal)
- Set up API keys from provider dashboards
- Enabled sandbox/testing mode for safe transaction testing

### Result

- Fully functional checkout system
- Support for multiple payment methods
- Ready for real-world deployment

---

## 🚚 Shipping & Discounts System

### Shipping Configuration

- Defined multiple shipping zones:
  - Italy
  - Europe
  - Rest of the World
- Implemented conditional shipping methods:
  - Standard shipping
  - Free shipping (based on order value)

### Coupons System

- Created multiple discount types:
  - Percentage discount
  - Fixed cart discount
- Configured usage limits and expiration rules

### Purpose

- Simulate a real-world eCommerce pricing and delivery system
- Improve conversion through discounts and flexible shipping options

---

## Tech Stack

- WordPress
- WooCommerce
- Wordfence Security
- WooCommerce CSV Import System

---

## Documentation

- [Setup Guide](setup-guide/installation.md)
- [Architecture](architecture/project-structure.md)
- [Security Details](security/security-notes.md)
- [Performance Notes](performance/optimization-notes.md)
- [Product Structure](product-structure/product-architecture.md)


---

## Live Demo

https://www.mardass.com/


---

## Notes

This project focuses on a practical WooCommerce implementation rather than custom backend development.

## 📸 Screenshots

### 🏠 Homepage
<img src="screenshots/homepage.png" width="500"/>

---

### 🛍️ Shop Page
<img src="screenshots/Shop.png" width="600"/>

---

### 📦 Product Page
<img src="screenshots/product.png" width="600"/>

---

### 📄 Other Pages

- [About Page](screenshots/about.png)
- [Contact Page](screenshots/contact.png)
- [FAQ Page](screenshots/faq.png)
- [Privacy Policy](screenshots/privacy-policy.png)
- [Terms & Conditions](screenshots/terms-and-conditions.png)
- [Refund Policy](screenshots/refund-policy.png)
- [Shipping Policy](screenshots/shipping-policy.png)
- [Cart (Slide-out Mini Cart)](screenshots/cart.png)
- [Checkout (Payment & Billing)](screenshots/checkout.png)
