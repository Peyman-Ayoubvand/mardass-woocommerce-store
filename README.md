# Mardass – WooCommerce Fashion Store

🚀 Fully customized WooCommerce store with improved UI/UX, responsive design, and real-world eCommerce functionality.

🔗 Live Demo: https://www.mardass.com/

---

## ✨ Key Features

- Custom product page layout (Flexbox-based gallery, no PHP modification)
- Advanced shop filtering system (price, size, color, category)
- Fully responsive custom homepage (desktop & mobile optimized)
- Slide-out mini cart (off-canvas UX)
- Stripe & PayPal payment integration
- SEO optimization (Rank Math + Search Console)
- Email marketing integration (Mailchimp popup system)

---

## Overview

This project documents the process of building and configuring a WooCommerce online store, focusing on security, structure, and practical implementation.

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
## 📄 Content & UX Pages

- Designed a brand-focused **About page** to communicate identity, values, and storytelling
- Created a structured **FAQ section** to address common user concerns and improve user experience

---

## 📜 Policies & Legal Pages

- Created essential legal pages for a complete eCommerce experience:
  - Privacy Policy
  - Terms & Conditions
  - Shipping Policy
  - Refund Policy

These pages were structured to reflect real-world online store requirements and improve user trust.

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

## 🔍 SEO Optimization

Basic on-page SEO improvements were implemented using Rank Math SEO.

### Focus Areas

- Optimized key pages:
  - Homepage
  - Shop page
  - Single product pages

- Defined focus keywords based on search intent
- Optimized SEO titles and meta descriptions
- Improved keyword placement across content and headings

### Implementation

- Used Rank Math SEO to analyze and improve page content
- Focused on increasing SEO score for main pages
- Improved readability and structure of content

### Google Search Console

- Connected website to Google Search Console
- Submitted the website for indexing
- Monitored indexed and non-indexed pages

### Result

- Improved SEO scores on key pages (Rank Math)
- Successful indexing of main pages
- Better visibility in search engine results

---

## 📞 Contact Page & Form Handling

A fully functional contact form was implemented using **WPForms** to allow users to easily reach out.

### Email Delivery Issue & Solution

During development, form submissions were not being delivered due to server email limitations.

To resolve this:

- Configured **WP Mail SMTP** for reliable email delivery
- Integrated SMTP authentication using a Gmail account
- Ensured successful form submission and email notifications

### Result

- Fully working contact form
- Reliable email delivery system
- Improved user communication experience

---

## 📧 Email Marketing Integration

Implemented basic email marketing functionality using Mailchimp.

### Popup Subscription

- Created a promotional popup offering a 10% discount
- Integrated popup using custom code (Code Snippets)
- Designed to capture user emails on site entry
- Connected popup form to Mailchimp audience list

### Email Campaign

- Designed a simple promotional email campaign
- Showcased selected products with direct links
- Maintained brand consistency in layout and visuals

### Result

- Functional email capture system
- Automated discount delivery via coupon code
- Improved potential for user retention and marketing

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
