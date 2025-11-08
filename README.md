# Thaalam Performing Arts Website

A modern, responsive single-page website for Thaalam Performing Arts, a non-profit organization dedicated to preserving and promoting Tamil percussion arts and cultural heritage.

## Features

- **Modern Design**: Clean, professional design optimized for non-profit organizations
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Single Page Layout**: Easy navigation with smooth scrolling between sections
- **Interactive Elements**: Animations, hover effects, and dynamic content
- **Contact Form**: Integrated contact form for visitor inquiries
- **Performance Optimized**: Fast loading times and smooth animations

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Information about Thaalam Performing Arts and its mission
3. **Parai**: Details about the traditional Tamil percussion instrument
4. **Programs**: Overview of classes, workshops, and cultural initiatives
5. **Contact**: Contact form and organization information
6. **Footer**: Quick links and additional information

## Technologies Used

- **HTML5**: Semantic markup for better accessibility
- **CSS3**: Modern styling with Flexbox and Grid layouts
- **JavaScript**: Interactive features and animations
- **Google Fonts**: Poppins and Playfair Display for elegant typography

## File Structure

```
Thaalam/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization

### Colors

The website uses a carefully selected color palette defined in CSS variables:

- Primary Color: `#c9302c` (Red)
- Secondary Color: `#d4a574` (Gold)
- Dark Color: `#2c1810` (Dark Brown)
- Light Color: `#f8f5f2` (Cream)

To change colors, edit the `:root` variables in `styles.css`.

### Content

To update content:

1. Open `index.html`
2. Locate the section you want to edit
3. Update the text content
4. Save and refresh your browser

### Images

The current design uses placeholder SVG graphics. To add real images:

1. Replace the `.image-placeholder` divs with `<img>` tags
2. Add your images to an `images/` folder
3. Update the image paths in the HTML

## Contact Form Setup

The contact form currently logs submissions to the browser console. To make it functional:

1. Set up a backend service (e.g., Formspree, Netlify Forms, or custom backend)
2. Update the form submission handler in `script.js`
3. Add the appropriate form action or API endpoint

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

This is a static website that can be hosted on:

- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply upload the files to your hosting provider.

## License

This website is created for Thaalam Performing Arts, a non-profit organization.

## About Thaalam

Thaalam Performing Arts is dedicated to preserving Tamil percussion arts and cultural heritage through education, performance, and community engagement. Learn more at [thaalamperformingarts.org](https://thaalamperformingarts.org)
