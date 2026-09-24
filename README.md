# Paradise Nursery Shopping Application

A React + Redux houseplant shopping app built for the IBM / Coursera **Developing Front-End Apps with React** final project.

## Features

- **Landing page** – company name, about paragraph, background image, and Get Started button
- **Product listing** – houseplants grouped into categories with Add to Cart
- **Shopping cart** – quantity controls, item totals, delete, continue shopping, and checkout

## Tech stack

- React (Vite)
- Redux Toolkit
- CSS

## Getting started

```bash
npm install
npm run dev
```

## Deploy to GitHub Pages

1. Update `base` in `vite.config.js` to match your repository name (e.g. `/your-repo-name`).
2. Add a deploy script if needed, then build and publish the `dist` folder:

```bash
npm run build
```

## Project structure

```
src/
  App.jsx          # Landing page + app shell
  App.css          # Landing page background styles
  AboutUs.jsx      # Company about section
  ProductList.jsx  # Product listing + navbar
  CartItem.jsx     # Shopping cart page
  CartSlice.jsx    # Redux cart slice
  store.js         # Redux store
```

## Source

Starter template: [ibm-developer-skills-network/e-plantShopping](https://github.com/ibm-developer-skills-network/e-plantShopping)
