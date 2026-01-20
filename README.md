# Portfolio Website - Ariel Berg

A modern, responsive portfolio website showcasing technical expertise and professional experience.

## Features

- **Modern Design**: Clean, professional UI with smooth animations
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Timeline**: Visual representation of work experience
- **Skills Showcase**: Organized skill categories with interactive tags
- **Smooth Navigation**: Fixed navbar with smooth scrolling
- **Contact Integration**: Direct links to phone and email

## Files Structure

```
.
├── index.html      # Main HTML structure
├── styles.css      # Styling and responsive design
├── script.js       # Interactive functionality and animations
├── cv.pdf          # Resume/CV document
└── README.md       # This file
```

## Getting Started

### Local Development

1. Simply open `index.html` in your web browser
2. Or use a local development server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

3. Navigate to `http://localhost:8000` in your browser

### Deployment

You can deploy this website to any static hosting service:

- **GitHub Pages**: Push to a GitHub repository and enable GitHub Pages
- **Netlify**: Drag and drop the folder or connect your Git repository
- **Vercel**: Connect your repository or use the CLI
- **AWS S3 + CloudFront**: Upload files to an S3 bucket
- **Any web server**: Upload all files to your web hosting provider

## Customization

### Update Contact Information

Edit the contact details in `index.html`:
- Hero section: Phone and email
- Contact section: Same information with icons

### Modify Work Experience

Edit the timeline items in the Experience section of `index.html`.

### Update Skills

Modify the skills grid in the Skills section of `index.html`.

### Change Colors

Update CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #64748b;
    /* ... other colors ... */
}
```

### Add Sections

You can easily add new sections by:
1. Creating a new section in `index.html`
2. Adding corresponding styles in `styles.css`
3. Updating navigation menu if needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (with CSS Variables, Flexbox, Grid)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

## License

This portfolio website is open source and available for personal use.

---

**Created by**: Ariel Berg  
**Last Updated**: 2024

# portfolio
