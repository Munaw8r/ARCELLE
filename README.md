# ARCELLE — D2C concept website

A responsive, multi-page front-end demo for a fictional premium handbag and women-entrepreneur community brand.

## Pages
- `index.html` — landing page / brand story / category entry points
- `shop.html` — full collection with category filters
- `work-edit.html` — work bags category
- `after-hours.html` — evening bags category
- `community.html` — curated community explainer + application form
- `story.html` — brand story
- `cart.html` — demo cart

## Run in VS Code
1. Extract the ZIP and open the `arcelle-d2c-site` folder in VS Code.
2. Install the **Live Server** extension if you don't already have it.
3. Right-click `index.html` → **Open with Live Server**.
   - You can also open `index.html` directly in a browser, but Live Server is better for local development.

## What works in this prototype
- Responsive layouts for desktop and mobile
- Product categories and product cards
- Add-to-bag, quantity changes, remove items, cart persistence using `localStorage`
- Community application form with required fields and a demo success state
- Newsletter form demo
- Mobile navigation

## Important limitations before a real launch
This is a front-end prototype, not a production ecommerce platform.
- Product images load from Unsplash and need replacing with licensed product photography.
- Prices, products, feature descriptions and brand identity are placeholders.
- Cart and community application data remain in the visitor's browser. No team receives applications.
- Checkout does **not** accept payment or create real orders. Connect a backend and a payment provider such as Razorpay/Stripe (subject to availability and account eligibility).
- For the private community, build a secure admin review workflow, protect applicant data, publish a privacy policy, and only grant access after an explicit approval.
- Connect email/CRM tools for application notifications and newsletter signups.
- Add actual shipping, returns, terms, privacy and contact details before going live.

## Change product details
Edit the `products` array near the top of `script.js`. Product `type` must be `work` or `evening`.

## Brand concept
**ARCELLE** — *Carry Your Ambition.*
- The Work Edit: laptop and business essentials
- The After Hours Edit: compact bags for dates, parties and evenings
- The Inner Circle: application-based community for women building businesses
