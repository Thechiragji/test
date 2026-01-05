# Images Directory

This directory is reserved for custom images for the AS Tour & Travels website.

## Current Setup

The website currently uses high-quality stock images from **Pexels** via CDN links, which means no local images are stored here. This approach:

- Reduces repository size
- Ensures fast loading times
- Uses professionally shot travel photography
- Requires no image hosting setup

## Adding Custom Images

If you want to use your own custom images instead of Pexels photos:

1. **Add your images to this directory**
   - Supported formats: JPG, PNG, WebP, SVG
   - Recommended sizes:
     - Hero banner: 1920x1080px
     - Package cards: 800x600px
     - Gallery items: 600x600px
     - Service icons: 100x100px (optional)

2. **Update the HTML file**
   - Replace Pexels URLs with local paths
   - Example: `src="images/hero-banner.jpg"`

3. **Update the CSS file**
   - Replace background-image URLs
   - Example: `background-image: url('../images/destination.jpg')`

## Recommended Image Optimization

Before adding images, optimize them for web:

- Use online tools like TinyPNG or ImageOptim
- Convert to WebP format for better compression
- Keep file sizes under 500KB for best performance
- Use responsive images with srcset for different screen sizes

## Image Attribution

If using free stock photos, remember to:
- Credit the photographer if required
- Check license terms (Pexels is free for commercial use)
- Keep attribution in your footer or credits page
