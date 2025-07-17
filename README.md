# Gisou Collective - Webflow Template

A sleek Webflow eCommerce template for modern art galleries. This template allows you to sell artworks online, showcase exhibitions, and publish blog content in a beautifully curated, responsive layout.

## Project Structure

```
webflowtemplate/
├── assets/
│   ├── css/
│   │   ├── normalize.css      # CSS reset and normalize styles (4.4KB)
│   │   ├── webflow.css        # Webflow framework styles (104KB)
│   │   └── main.css           # Custom project styles (196KB)
│   └── images/                # Image assets (future use)
├── pages/
│   └── home.html              # Main homepage (includes inline JavaScript)
├── docs/                      # Documentation files
└── README.md                  # This file
```

## File Organization

### CSS Files

The CSS architecture follows a layered approach for optimal maintainability and performance:

- **normalize.css** (4.4KB): CSS reset and normalize styles for cross-browser compatibility
- **webflow.css** (104KB): Webflow framework styles including icons, components, and widgets
- **main.css** (196KB): Custom project-specific styles for the Gisou Collective template

**CSS Loading Order**: Files are loaded in the correct cascade order:

1. `normalize.css` - Establishes consistent base styles
2. `webflow.css` - Provides framework components
3. `main.css` - Applies custom overrides and project-specific styles

**Adding New CSS Files**: When adding additional CSS files, maintain this loading order:

- Base/Reset styles first
- Framework styles second
- Component styles (if added)
- Utility styles (if added)
- Custom/override styles last

### HTML Files

- **pages/home.html**: The main homepage template with navigation, hero section, and content areas
  - Contains inline JavaScript (no separate JS files needed)
  - Links to CSS files using relative paths: `../assets/css/`

## Getting Started

1. **Clone or download** this repository
2. **Open** `pages/home.html` in your web browser to view the template
3. **Customize** the content in `pages/home.html` to match your needs
4. **Modify** styles in `assets/css/main.css` for custom styling
5. **Add images** to the `assets/images/` directory as needed

## Development

### CSS Structure

The CSS is organized in three layers:

1. **Base Layer** (normalize.css): Browser resets and base styles
2. **Framework Layer** (webflow.css): Webflow component styles
3. **Custom Layer** (main.css): Project-specific customizations

### Adding New Pages

1. Create new HTML files in the `pages/` directory
2. Link to the CSS files using relative paths: `../assets/css/`
3. Follow the same structure as `home.html`

### Adding JavaScript

- JavaScript should be included inline within HTML files
- Use `<script>` tags in the `<head>` or before closing `</body>` tag as needed
- External libraries can be linked via CDN (as shown in the existing template)

## Features

- Responsive design optimized for all devices
- Modern art gallery layout
- eCommerce functionality (Webflow CMS integration)
- Blog content support
- Clean, professional design
- Cross-browser compatibility

## Browser Support

This template supports all modern browsers including:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This is a Webflow template. Please refer to Webflow's licensing terms for usage rights.

## Support

For questions about this template organization or structure, please refer to the documentation in the `docs/` directory.
