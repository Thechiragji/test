# AS Tour & Travels - Premium Travel Agency Website

A modern, fully responsive travel agency website built with vanilla HTML, CSS, and JavaScript. This frontend-only website showcases tour packages, services, and provides a complete user experience for travel booking inquiries.

## Features

- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations and transitions
- **Interactive Components** - Dynamic navigation, search functionality, and form validation
- **Premium Look** - Travel-themed color palette with dark blue, white, and accent orange
- **Multiple Sections** - Hero, Services, Packages, Gallery, Testimonials, Contact, and more
- **No Dependencies** - Pure HTML5, CSS3, and vanilla JavaScript (ES6)

## Project Structure

```
/travel-website
│── index.html          # Main HTML file
│── css/
│   └── style.css      # All styles and responsive design
│── js/
│   └── script.js      # Interactive functionality
│── images/            # Placeholder for custom images
└── README.md          # Project documentation
```

## Sections Overview

### 1. Header
- Sticky navigation bar
- Mobile-responsive hamburger menu
- Smooth scroll navigation
- Active section highlighting

### 2. Hero Section
- Full-width banner with overlay
- Call-to-action buttons
- Integrated search bar (Destination, Date, Budget)
- WhatsApp contact integration

### 3. Our Services
- Flight Booking
- Train Booking
- Hotel Booking
- Cab Services
- Passport & Visa Assistance
- Char Dham Yatra Packages

### 4. Popular Tour Packages
- Manali Honeymoon Package
- Goa Beach Paradise
- Kerala Backwaters
- Rajasthan Heritage Tour
- Ladakh Adventure
- Char Dham Yatra

### 5. Why Choose Us
- Trusted Agency
- Affordable Pricing
- 24/7 Support
- Experienced Team

### 6. Gallery
- Responsive grid layout
- Hover zoom effects
- Lightbox image viewer

### 7. Testimonials
- Customer reviews
- Star ratings
- Real experiences

### 8. Contact Section
- Contact form with validation
- Google Maps integration
- WhatsApp contact button
- Business information

### 9. Footer
- Company information
- Quick links
- Contact details
- Social media icons

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, Custom Properties, Animations
- **JavaScript ES6** - Modern vanilla JavaScript
- **Pexels Images** - Free stock photography for demo purposes

## Key Features Implementation

### Responsive Navigation
- Desktop: Horizontal navigation bar
- Mobile: Hamburger menu with smooth toggle animation
- Sticky header on scroll

### Search Functionality
- Destination input validation
- Date picker with minimum date restriction
- Budget selection dropdown
- Real-time notifications

### Form Validation
- Required field validation
- Email format validation
- Phone number validation
- Success/error notifications

### Scroll Animations
- Fade-in animations on scroll
- Intersection Observer API
- Smooth scroll behavior

### Interactive Elements
- Hover effects on cards
- Button interactions
- Gallery lightbox
- Scroll-to-top button

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Setup & Installation

1. **Open the project**
   - Simply open `index.html` in your web browser
   - No build process or dependencies required

2. **For local development server (optional)**
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve

   # Using PHP
   php -S localhost:8000
   ```

3. **Access the website**
   - Direct: Open `index.html` in browser
   - Server: Navigate to `http://localhost:8000`

## Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select branch (main/master)
4. Save and wait for deployment

### Netlify
1. Drag and drop the project folder
2. Or connect GitHub repository
3. Deploy automatically

### Vercel
1. Import GitHub repository
2. Configure build settings (none required)
3. Deploy

## Customization Guide

### Colors
Edit CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #1e3a5f;    /* Dark blue */
    --secondary-color: #ff6b35;   /* Orange */
    --accent-color: #f7931e;      /* Light orange */
}
```

### Content
- Update text content in `index.html`
- Modify package details, prices, and descriptions
- Change contact information in footer and contact section

### Images
- Replace Pexels URLs with your own images
- Add custom images to `/images` folder
- Update image paths in HTML and CSS

### Functionality
- Extend JavaScript in `js/script.js`
- Add backend integration (contact form, booking system)
- Connect to API for dynamic content

## Performance Optimizations

- Optimized images from Pexels CDN
- Minimal CSS with no frameworks
- Vanilla JavaScript (no heavy libraries)
- Efficient animations using CSS transforms
- Lazy loading for scroll animations

## SEO Considerations

- Semantic HTML5 markup
- Meta tags for description
- Proper heading hierarchy
- Alt attributes ready for images
- Mobile-friendly responsive design

## Future Enhancements

- Backend integration for contact form
- Booking system with payment gateway
- Admin panel for package management
- Customer review system
- Live chat support
- Multi-language support
- Blog section
- Newsletter subscription

## Contact & Support

For any inquiries or support:
- **Email**: info@astours.com
- **Phone**: +91 98765 43210
- **WhatsApp**: [Click to chat](https://wa.me/919876543210)

## License

This project is open source and available for personal and commercial use.

## Credits

- **Design & Development**: AS Tour & Travels
- **Images**: [Pexels](https://www.pexels.com) - Free stock photos
- **Icons**: Unicode Emoji characters

---

**Built with passion for travelers by AS Tour & Travels**

*Plan Your Perfect Journey With Us!*