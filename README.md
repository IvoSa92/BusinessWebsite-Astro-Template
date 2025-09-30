# Business Website Astro Template

This project provides a ready-to-use marketing website built with Astro v5 and LESS styling. It includes polished components for common business pages so you can move straight to content and brand tweaks without worrying about boilerplate setup.

## Features
- Astro 5 project configured for static deployments.
- Pre-built pages for Home, About, Projects, Reviews, and Contact.
- Responsive navigation with mobile menu and optional dark mode toggle.
- Centralized data files for navigation, client details, and reusable content.
- LESS-based styling with helpful variables and light/dark theme support.

## Getting Started
1. Install dependencies with `npm install`.
2. Run the local dev server with `npm run dev`.
3. Open `http://localhost:4321` in your browser.
4. Update assets and content to match your brand, then run `npm run build` for production output.

## Project Structure
```
├── public/                # Static assets served as-is
├── src/
│   ├── assets/            # Images used by Astro components
│   ├── components/        # Reusable Astro components
│   ├── data/              # JSON data sources (nav, client info, etc.)
│   ├── layouts/           # Top-level page layouts
│   ├── pages/             # Astro pages for each route
│   ├── styles/            # Global and component styles written in LESS
│   └── js/                # Small client-side scripts
└── astro.config.mjs       # Astro configuration
```

## Customization Tips
- Update navigation links and labels in `src/data/navData.json`.
- Adjust global branding, colors, and typography in `src/styles/root.less` and `src/styles/dark.less`.
- Replace copy and imagery within the Astro page files in `src/pages/`.
- Modify shared client information (name, address, social links) in `src/data/client.json`.

## Deployment
Run `npm run build` to generate the static site in the `dist/` directory, then deploy the output to your preferred hosting provider (Netlify, Vercel, GitHub Pages, etc.).

## License
This template is distributed under the MIT License. See `LICENSE` for details.
