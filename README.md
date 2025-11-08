# தாளம் Thaalam Performing Arts Website

A modern, responsive single-page website for Thaalam Performing Arts, a 501(c)(3) non-profit organization celebrating Traditional South Indian Arts and supporting folk communities in Tamil Nadu.

## About Thaalam Performing Arts

Thaalam Performing Arts preserves heritage through Thaalam, Karagattam and folk performances while raising funds to support folk communities in Tamil Nadu. The organization's mission is to preserve and promote the rich cultural heritage of South Indian performing arts while making a meaningful impact on the lives of underserved communities.

## Features

- **Modern Non-Profit Design**: Professional, clean design optimized for cultural organizations
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Single Page Layout**: Easy navigation with smooth scrolling between sections
- **Interactive Elements**: Smooth animations, hover effects, and engaging transitions
- **Contact Form**: Integrated contact form for inquiries and support
- **Mission-Focused**: Clear messaging about cultural preservation and community impact

## Sections

1. **Hero Section**: Eye-catching introduction highlighting the 501(c)(3) status and mission
2. **Our Mission**: Detailed mission statement and organizational pillars
3. **Traditional Art Forms**: Information about Thaalam, Karagattam, and folk performances
4. **Our Impact**: Details about performances, community support, and cultural education
5. **Contact**: Contact form and organization information
6. **Footer**: Quick links and additional organizational details

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
