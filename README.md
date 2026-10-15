# Form & Field — React E-commerce Store

A responsive e-commerce storefront built with React, Vite, plain CSS, and Lucide icons.

## Requirements
- Node.js (LTS recommended)
- npm

## Run locally
1. Extract this folder and open it in VS Code.
2. Open the VS Code terminal in this folder.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open the local URL printed in the terminal (usually `http://localhost:5173`).

## Included functionality
- Responsive layout and mobile navigation
- Product search and category filters
- Add-to-cart, remove, and quantity controls
- Live cart count, subtotal, and free-shipping progress
- Favorites toggle
- Newsletter form validation (demo only)
- Demo checkout notice (no payment is processed)

## Notes
Product photography loads from Unsplash and Google Fonts are loaded online. The cart is in React state, so it resets when the page is refreshed. Checkout and newsletter subscription are front-end demos and are not connected to a payment or email service.
