# Nice Gadgets Store

A modern, responsive e-commerce web application for browsing and purchasing tech products, including smartphones, tablets, and accessories. This project demonstrates clean architecture, dynamic routing, and efficient global state management.

## Live Preview

[🚀 View Live Demo](https://1umamaster.github.io/NiceGadgets_store/)

## Design Reference

The application UI/UX is based on a professional design mockup:
[🎨 Figma Design](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog--V2--Original?m=auto&t=WVvqall6TgxIfq8g-6)

## Technologies Used

- **React 18** (Functional Components, Hooks)
- **TypeScript** (Strict typing and interfaces)
- **Vite** (Next-generation frontend tooling)
- **React Router** (Dynamic SPA routing)
- **SCSS / CSS Modules** (BEM methodology, mixins, and variables)
- **Context API** (Global state management for Cart and Favorites)

## Features

- **Optimized Data Fetching:** Categorized data retrieval to minimize payload size and improve page load speed.
- **Responsive UI:** Mobile-first approach using SCSS mixins to ensure a flawless experience across all screen sizes.
- **Dynamic Product Configuration:** Real-time validation of available device colors and storage capacities based on database inventory.
- **Global Cart Management:** Add, remove, and calculate total prices seamlessly across the application, complete with intuitive empty states.
- **Dynamic SEO Headings:** Custom hooks to dynamically update document titles based on the active route and product.

## Getting Started

Follow these instructions to set up the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/1umamaster/NiceGadgets_store.git
   cd NiceGadgets_store

2. **Install dependencies:**
   ```bash
   npm install

3. **Run the project locally:**
   ```bash
   npm start
