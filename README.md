# My Personal Website

## Overview

This website is a barebones little thing that serves as a central hub to share my projects and provide a point of contact. I might also decide to blog at some point. 

## Tech Stack

This website is built with modern web technologies, focusing on performance and a good developer experience:

*   **[Astro](https://astro.build/):** The core static site generator, enabling a fast, content-focused website with excellent performance. Astro allows for component-based architecture using `.astro` files, which can also seamlessly integrate UI framework components (though primarily vanilla JS/CSS is used here). Way faster than next.js with a super simplistic codebase structure. 
*   **HTML5:** Semantic markup for structuring the content.
*   **CSS3:** Custom styling for the visual presentation, including:
    *   CSS Variables for theming (colors, fonts, spacing).
    *   Flexbox and Grid for layout.
    *   Keyframe animations for dynamic page elements.
*   **JavaScript (Vanilla):** Used for interactive elements, such as smooth scrolling, animations, and dynamic content updates (e.g., auto-hiding header, dynamic year in footer).

## Key Features

*   Minimal orange-cream GUI with an Apple-like aesthetic.
*   Smooth page transitions and element animations.
*   Responsive design for various screen sizes.
*   Sticky/auto-hiding navigation.
*   Individual landing pages for showcased applications.
*   Clear and intuitive navigation.

## Project Structure

The project follows a standard Astro project layout:

```
silly-website/
├── public/               # Static assets (images, icons, fonts)
├── src/
│   ├── components/       # Reusable UI components (.astro)
│   ├── layouts/          # Base page layouts (.astro)
│   ├── pages/            # Site pages and app landing pages (.astro, .md)
│   ├── styles/           # Global CSS and styles
├── astro.config.mjs      # Astro configuration
├── package.json          # Project dependencies and scripts
└── tsconfig.json         # TypeScript configuration (if using TS)
```

## Getting Started (Development)

If you would like to clone my website for your own use, feel free to! 

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/0xCUB3/silly-website
    cd silly-website
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    # or yarn install, pnpm install
    ```
3.  **Run the development server:**
    ```bash
    npm run dev
    ```
    This will start a local development server, typically at `http://localhost:4321/`.

4.  **Build for production:**
    ```bash
    npm run build
    ```
    This will generate the static site in the `dist/` directory.