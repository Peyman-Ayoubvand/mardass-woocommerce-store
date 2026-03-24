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

## 🛍️ Product Page (Custom UI)

- Redesigned WooCommerce product gallery layout using pure CSS (Flexbox)
- Moved thumbnails to a vertical sidebar layout (desktop & tablet)
- Improved visual hierarchy and image interaction (hover effects, scaling)
- Implemented fully responsive behavior for mobile devices (horizontal thumbnails)
- Enhanced overall product page UX without modifying WooCommerce core files

---

## 🛍️ Shop Page (Filtering System)

- Implemented a sidebar-based product filtering system (price, size, color, category)
- Integrated product search functionality within the shop page
- Configured and structured the shop layout into a sidebar-based layout
- Optimized filtering UX for both desktop and mobile devices
- Improved product browsing experience with better layout and accessibility

---

## 🏠 Homepage (Custom Design & UX)

- Designed a fully custom homepage using Elementor with multiple sections
- Implemented a video-based hero section for strong visual impact (desktop/tablet)
- Created a separate mobile-optimized hero section for better performance
- Built interactive product showcase sections (e.g., New Arrivals)
- Designed key sections including Best Seller, Brand Story, and Testimonials
- Structured responsive layouts for different devices (desktop, tablet, mobile)
- Focused on clean, minimal UI aligned with a fashion brand identity

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

## 🛒 Cart & Checkout (UX Optimization)

- Implemented a slide-out mini cart using a WooCommerce plugin and customized its UI
- Improved shopping flow by reducing page reload dependency
- Enhanced cart usability with better layout and readability
- Optimized checkout layout for clearer form structure
- Integrated multiple payment methods (Stripe & PayPal)
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

## 🛠 Tech Stack

- WordPress (Astra Theme)
- WooCommerce
- Elementor (Page Builder)
- CSS (Flexbox, responsive design, UI customization)
- JavaScript (basic UI interactions)
- Stripe & PayPal (payment integration)
- Mailchimp (email marketing)
- Wordfence (security)
- 
---

## Live Demo

https://www.mardass.com/

---

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
