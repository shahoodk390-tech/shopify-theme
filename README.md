# Walmart Theme

A modern, enterprise-grade Walmart-style e-commerce theme with a clean, efficient design focused on performance and user experience.

## Features

- **Clean, Minimalist Design**: Walmart-inspired layout with focus on product visibility
- **Responsive Layout**: Mobile-first approach for all devices
- **High Performance**: Optimized asset loading and lazy loading
- **Accessibility**: WCAG compliant design standards
- **Modern Build Pipeline**: Webpack 5 with optimization
- **Modular Components**: Reusable liquid snippets and sections
- **Easy Customization**: Well-organized config structure

## Project Structure

```
walmart-theme/
├── assets/          # CSS, JS, and image files
├── config/          # Theme settings and configuration
├── layout/          # Theme layout files (theme.liquid)
├── locales/         # Translation files
├── sections/        # Dynamic sections (Shopify 2.0)
├── snippets/        # Reusable liquid components
├── templates/       # Page templates
├── package.json     # Dependencies and scripts
└── webpack.config.js # Build configuration
```

## Installation

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```

## Development

Start the development server with file watching:

```bash
npm run dev
```

This will:
- Watch for file changes in assets
- Rebuild CSS and JavaScript automatically
- Output optimized files to `dist/`

## Production Build

Create optimized production assets:

```bash
npm run build
```

## Deployment

1. Build the theme:
   ```bash
   npm run build
   ```

2. Upload to Shopify using Shopify CLI:
   ```bash
   shopify theme push
   ```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT

## Author

shahoodk390-tech
