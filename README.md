# AyuLanka multi-page storefront (prototype)

## Pages
- `index.html` — homepage
- `category.html` — Ayurveda, groceries and all products
- `product.html` — product detail
- `cart.html` — shopping cart
- `checkout.html` — WhatsApp order request
- `admin.html` — local demo product manager
- `styles.css` and `app.js` — shared design and functionality

## Add your products
Open `admin.html` and add products. In this prototype, product data is stored in the current browser's LocalStorage only. It is not a secure owner dashboard and other visitors will not see the products you add.

## Publish
Upload all files to a static host such as Cloudflare Pages. Keep all files in the same folder/root. The site can be previewed by opening `index.html`.

## Important before real business use
This is a static frontend prototype. It does not provide real customer accounts, secure admin login, shared product inventory, persistent orders, inventory synchronization or online payments. Those require a backend/database and server-side security. Do not publish `admin.html` as a real protected admin panel until authentication and authorization are implemented.
