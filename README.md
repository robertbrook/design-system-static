# design-system-static

## External Dependencies

This repository contains static assets for a design system. The following external dependencies are bundled within the static files:

### CSS Framework
- **Bootstrap v4.5.3**
  - Source: https://getbootstrap.com/
  - License: MIT License
  - Copyright: 2011-2020 The Bootstrap Authors
  - Bundled in: `styles.css`

### Icon Library  
- **Font Awesome Free 5.13.0**
  - Source: https://fontawesome.com/
  - License: Mixed (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License)
  - Font files bundled in: `webfonts/` directory
    - `fa-brands-400.woff2`
    - `fa-regular-400.woff2` 
    - `fa-solid-900.woff2`
  - CSS bundled in: `styles.css`

### Custom Fonts
- **National Font Family**
  - Font files bundled in: `fonts/` directory
    - `National-LFS-Book.woff2`
    - `National-LFS-Semibold.woff2`
  - CSS definitions bundled in: `styles.css`

### JavaScript
- **Custom Design System Components** (no external dependencies)
  - Primary navigation functionality
  - Tab accessibility features
  - Browser polyfills for older browser support
  - Bundled in: `umd/index.min.js`

### Icons
- **Custom Parliamentary Icons**
  - SVG sprite bundled in: `assets/p-icons.svg`

## Notes

All external dependencies have been bundled into the static assets, so no external CDN requests or package manager installations are required. The repository serves as a self-contained distribution of the design system.
