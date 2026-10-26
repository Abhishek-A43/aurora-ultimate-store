# AURORA Ultimate Store — E-commerce Front-End

A premium, dark editorial storefront built with HTML, CSS and vanilla JavaScript. It is a front-end demo that you can customize.

## Included
- Premium dark design, responsive mobile/tablet/desktop layout
- Animated hero product, marquee, image hover transitions, category cards
- Product catalogue with categories, search, sorting, product detail modal
- Shopping cart with quantity changes, remove item, subtotal and browser localStorage persistence
- Wishlist / save for later
- Compare tray (up to 3 products)
- Demo sign-in form and demo checkout/order confirmation
- Newsletter UI interaction
- Unique “Vibe Finder” and “Surprise Me” product discovery
- INR pricing and sample product content

## Run locally
1. Extract `aurora-ultimate-store.zip`.
2. Open `index.html` in Chrome/Edge/Firefox.
3. For development, open the folder in VS Code and use Live Server.

## Customize products
Open `js/app.js` and edit the `products` array. Each product has:
- `name`, `cat`, `price`, `old`, `tag`, `rating`, `reviews`
- `image` (replace with your own image URL or local path)
- `desc` and `vibe`

Product images are external Unsplash sample photos. Replace them with images you have rights to use. Internet is needed for remote images and Google Fonts.

## Important
This is not yet a production store. Login is demo-only, checkout does not charge or save a real order, newsletter does not subscribe users, and there is no server/database. For real use, add a backend/API, authentication, order storage, inventory and a payment provider (such as Razorpay/Stripe) with secure server-side verification. Never collect real customer passwords or payment details in this demo.
