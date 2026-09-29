# MORI

A fictional modern Nigerian food ordering website concept. MORI is a placeholder brand built around a simple idea: **good food, simply made.**

The project demonstrates a polished restaurant ordering experience while keeping the implementation lightweight and entirely front-end based.

## Overview

MORI provides customers with:

- A modern restaurant landing page
- Menu browsing by category
- Existing concept menu items and Nigerian naira pricing
- Shopping cart functionality
- Pickup and delivery selection
- Customer details collection
- Nigerian phone number validation
- Automatic order receipt generation
- Receipt image download
- WhatsApp-style order handoff flow
- Responsive, mobile-friendly navigation

> **Note:** MORI is a fictional placeholder concept. Contact details and brand information are intentionally non-production placeholders.

## Ordering Flow

1. Customer browses the menu.
2. Customer selects items and adds them to the cart.
3. Customer reviews the order.
4. Customer chooses **Pickup** or **Delivery**.
5. Customer enters their name and phone number.
6. For delivery, the customer provides an address.
7. The website generates an order receipt.
8. Customer can save the receipt as an image.
9. The checkout flow provides a WhatsApp handoff for the order.

## Key Features

### Menu

The menu is organized into categories such as:

- Meals
- Noodles
- Combos
- Sides
- Drinks
- Food Bowls

Menu items and prices are retained from the supplied reference project for demonstration purposes.

### Shopping Cart

Customers can:

- Add items to their cart
- Increase or decrease quantities
- Remove items
- Review selected items
- View the running order total
- Continue browsing without being automatically redirected to the cart

Cart data is stored locally in the customer's browser using localStorage.

### Receipt Generation

The checkout flow generates a MORI-branded receipt containing:

- MORI identity
- Order information
- Selected items
- Quantities
- Customer details
- Order type
- Total amount

The receipt can be saved as an image and manually attached when completing the order handoff.

### Order Handoff

The project uses a WhatsApp deep-link style flow for the final order handoff.

The customer can generate their receipt, save it, and then open the configured placeholder WhatsApp destination.

> Delivery details are treated separately from the displayed menu total.

## Technology

The project intentionally uses a lightweight architecture:

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage
- HTML Canvas API
- WhatsApp deep linking

No backend or database is required for the current demonstration flow.

## Project Structure

    Noonandco/
    ├── assets/
    │   └── images and supporting assets
    ├── css/
    │   └── style.css
    ├── js/
    │   ├── data.js
    │   ├── cart.js
    │   ├── checkout.js
    │   ├── main.js
    │   └── menu.js
    ├── index.html
    ├── menu.html
    ├── cart.html
    └── README.md

## Local Development

Because MORI is a static website, it can be run without a backend.

Clone the repository:

    git clone https://github.com/KHLLD00/Noonandco.git

Open the project in a code editor and launch it using a local development server.

For example, with VS Code, the project can be opened with a static-server extension such as Live Server.

## Deployment

The website can be deployed using:

- GitHub Pages
- Netlify
- Vercel
- Any other static hosting provider

No server-side runtime is required for the current implementation.

## Important Notes

- MORI is a fictional placeholder brand.
- Contact information in the project is placeholder information.
- The menu products and prices are retained for demonstration.
- Orders are not stored in a central database.
- Cart data is stored locally in the customer's browser.
- The current order handoff is client-side.
- Delivery information is not calculated by a backend.
- This repository is intended as a front-end concept/demo.

## Project Status

**Status:** Active development

The MORI project is a fictional restaurant website concept focused on demonstrating a clean, modern ordering experience with a lightweight front-end architecture.
