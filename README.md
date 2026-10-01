# Clothes Store — React Storefront

A clothing e-commerce storefront built with React, TypeScript, and Tailwind CSS.

## Features

- Product catalog with a modal product-detail view
- Shopping cart (add, remove, quantity updates)
- Responsive navbar and hero section
- Smooth animations via Framer Motion

## Tech Stack

- React 18 + TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Lucide icons

## Getting Started

The project lives in the `project/` folder of this repo.

```bash
cd project
npm install
npm run dev
```

Build for production with `npm run build`, preview the build with `npm run preview`.

## Project Structure

```
project/
├── src/
│   ├── App.tsx              # Main app shell — hero, product grid, cart state
│   ├── components/
│   │   ├── Navbar.tsx
│   │   ├── ProductCard.tsx
│   │   ├── ProductModal.tsx
│   │   └── CartModal.tsx
│   └── data/products.ts     # Local product catalog
```

## Notes

Product data is currently defined locally in `src/data/products.ts` — there is no backend or database wired up.
