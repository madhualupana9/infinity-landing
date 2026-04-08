# Repository Guidelines

This repository contains a landing page built with WordPress, likely as a static export or a minimal local installation.

## Project Structure & Module Organization
The project follows a standard WordPress frontend structure, primarily focused on serving a single landing page through `index.html`.

- **index.html**: The main entry point containing the full page structure, styles (Astra & Elementor), and scripts.
- **wp-content/uploads/**: Contains all media assets, including optimized WebP images and Elementor-specific CSS/JS.
- **xmlrpc.php**: Standard WordPress XML-RPC endpoint.

## Technologies & Frameworks
The landing page is constructed using the following core technologies:
- **WordPress 6.8.1**: Core CMS (source).
- **Astra Theme**: The base theme providing structural CSS.
- **Elementor 3.31.1**: Page builder used for layout and content.
- **Premium Addons for Elementor**: Additional UI components.
- **Site Kit by Google**: Integration for analytics and search console.

## Coding Style & Naming Conventions
As a static/WordPress export, the repository follows standard web development conventions:
- **HTML/CSS**: Inline critical CSS is used for performance, while external assets are loaded from `wp-content/uploads/`.
- **Assets**: Images are primarily in `.webp` format for optimization.

## Development Notes
- There are no active build scripts or test suites in this repository.
- Changes should be made directly to `index.html` or by updating assets in `wp-content/uploads/`.
- Ensure any new images are optimized and placed in the appropriate directory within `wp-content/uploads/`.
