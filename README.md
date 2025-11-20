# Jaynie Ng - Personal Portfolio Website

A vibrant, pop-art inspired personal portfolio website featuring a comic book aesthetic with bold colors and playful illustrations.

## Overview

This is a single-page portfolio website that showcases a creative grid-based layout with hand-drawn SVG illustrations. The design features a warm color palette with purple, mint, lime, amber, and peach tones against a paper-like background.

## Features

- **Responsive Design**: Adapts seamlessly from desktop to mobile devices
- **Comic Book Aesthetic**: Bold outlines and playful SVG illustrations
- **Grid Layout**: Modern CSS Grid-based layout with decorative tiles
- **Smooth Navigation**: In-page anchor links to About, Projects, and Writing sections
- **Custom Illustrations**: Hand-crafted SVG graphics including faces, flowers, and geometric shapes

## Color Palette

- **Purple** (`#AD82D9`)
- **Mint/Cyan** (`#79D9C7`)
- **Lime** (`#A9D979`)
- **Amber/Gold** (`#F2B33D`)
- **Peach** (`#F29C94`)
- **Paper** (`#F5F0E8`) - warm off-white background
- **Ink** (`#121212`) - near-black for text and outlines

## Project Structure

```
jaynie-ng/
├── index.html      # Main HTML file
├── style.css       # Stylesheet with custom CSS Grid layout
├── CNAME          # Custom domain configuration
└── README.md      # This file
```

## Technologies Used

- HTML5
- CSS3 (CSS Grid, Flexbox)
- SVG Graphics
- Vanilla JavaScript (for dynamic copyright year)

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/jaynie-ng/jaynie-ng.git
   ```

2. Navigate to the project directory:
   ```bash
   cd jaynie-ng
   ```

3. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js (npx)
   npx serve
   ```

4. Visit `http://localhost:8000` in your browser

## Deployment

This site is configured to use a custom domain via the CNAME file:
- **Domain**: jaynieng.com

The site can be deployed using GitHub Pages or any static hosting service.

## Sections

- **Hero**: Large title block with greeting
- **About Me**: Introduction section
- **Projects**: Portfolio of work
- **State of the Art**: Writing/blog section

## Customization

To customize the color scheme, modify the CSS variables in [style.css](style.css):

```css
:root {
  --c1: #AD82D9; /* purple */
  --c2: #79D9C7; /* mint/cyan */
  --c3: #A9D979; /* lime */
  --c4: #F2B33D; /* amber */
  --c5: #F29C94; /* peach */
  --paper: #F5F0E8;
  --ink: #121212;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2025 Jaynie Ng. All rights reserved.

## Contact

For inquiries, please visit [jaynieng.com](https://jaynieng.com)
