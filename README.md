# VitrinesPro

A modern, responsive static homepage for vitrinespro.com.br, a platform focused on promoting and selling both physical and digital products.

## Project Structure

```
.
├── index.html       # Main homepage
├── styles.css       # Stylesheet
├── script.js        # JavaScript for smooth scrolling
└── README.md        # This file
```

## Features

- Clean, modern design with gradient hero section
- Fully responsive (mobile, tablet, desktop)
- Smooth scrolling navigation
- Semantic HTML5 structure
- Lightweight CSS (no frameworks)
- Easy to extend for future subpages

## Content

- **Hero Section**: Welcome message with headline, subheadline, and description
- **About Section**: Brief description of VitrinesPro
- **Products Section**: Placeholder for upcoming products
- **Footer**: Copyright and navigation links

## GitHub Pages Deployment

This project is set up to be deployed automatically on GitHub Pages:

1. Push to the `main` branch
2. Go to repository settings
3. Enable GitHub Pages
4. The site will be available at `https://username.github.io/vitrinespro/`

## Future Expansion

The structure is designed to easily add subpages:
- Create new folders (e.g., `unhas/`, `ebooks/`)
- Each folder can have its own `index.html`
- Or create separate HTML files like `products.html`, `about.html`, etc.

## Local Development

Simply open `index.html` in a web browser or use a local server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve
```

Then visit `http://localhost:8000`

## License

© 2024 VitrinesPro. All rights reserved.

