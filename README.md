# Trendyol Storefront

A responsive shopping demo with a Turkish interface, product discovery, favorites, and a persistent shopping cart.

## Getting started

```sh
npm install
npm run dev
```

Open http://localhost:3000. If Windows PowerShell blocks npm scripts, use `npm.cmd` instead of `npm`.

To build and run the production version:

```sh
npm run build
npm start
```

## Features

- Search products, filter by category, and sort by price.
- Save favorite products and manage cart quantities.
- Keep favorites and cart contents in the browser using localStorage.
- Browse responsive category menus, promotional sections, and product cards.
- Display an empty state when no sample products match the selected category or search.

## Project structure

- `app/page.js`: storefront, interactions, and styling utilities.
- `app/layout.js`: root layout and page metadata.
- `app/globals.css`: stylesheet entry point, fonts, and shared base styles.
- `postcss.config.mjs`: stylesheet build configuration.

## Demo limitations

Products and promotions are sample content. Payment, account, seller, and order services are not connected. Photos load from Unsplash and fonts load from Google Fonts, so these assets require an internet connection.
