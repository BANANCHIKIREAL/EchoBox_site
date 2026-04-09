# EchoBox Website

Modern, responsive website for the EchoBox audio player application.

## Features

- **Modern Design**: Clean, intuitive interface inspired by the EchoBox app
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Parallax effects, hover states, and scroll animations
- **Interactive Elements**: Functional navigation, download buttons, and copy-to-clipboard
- **Performance Optimized**: Debounced scroll events and efficient animations
- **Accessibility**: Semantic HTML5 structure with proper ARIA labels

## Technologies Used

- **HTML5**: Semantic markup with modern features
- **CSS3**: Flexbox, Grid, custom properties, and animations
- **JavaScript**: Vanilla JS with ES6+ features
- **Google Fonts**: Inter font family for modern typography

## File Structure

```
website/
|-- index.html          # Main HTML file
|-- styles.css          # Complete styling with responsive design
|-- script.js           # Interactive functionality and animations
|-- README.md           # This file
```

## Key Features

### Navigation
- Fixed header with blur effect
- Mobile-responsive hamburger menu
- Active section highlighting
- Smooth scrolling between sections

### Hero Section
- Eye-catching title with emoji
- App preview with 3D perspective effect
- Feature statistics
- Call-to-action buttons with ripple effects

### Features Section
- Grid layout for feature cards
- Hover animations and transitions
- Icon-based visual representation

### Download Section
- Multiple download options
- System requirements display
- Copy-to-clipboard functionality for commands
- Interactive download simulation

### About Section
- Version information and changelog
- Feature highlights
- Responsive grid layout

## Customization

### Colors
The website uses CSS custom properties that match the EchoBox app:
- Primary: `#007AFF` (blue)
- Success: `#34C759` (green)  
- Danger: `#FF3B30` (red)
- Background: `#F5F5F7` (light gray)

### Typography
Uses Inter font family for modern, clean text rendering.

### Animations
- Fade-in animations on scroll
- Parallax effects
- Button hover states
- Progress bar animations

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance

- Optimized CSS with efficient selectors
- Debounced scroll events
- Lazy loading animations
- Minimal JavaScript footprint

## Getting Started

1. Copy all files to your web server
2. Ensure proper MIME types are configured
3. Update links and contact information as needed
4. Deploy and enjoy!

## Customization Tips

### Updating Colors
Edit the CSS custom properties in `:root` section of `styles.css`:

```css
:root {
    --primary-color: #your-color;
    --primary-hover: #your-hover-color;
    /* ... other colors */
}
```

### Adding New Sections
1. Add new `<section>` with appropriate ID
2. Update navigation menu with new link
3. Add corresponding styles
4. Update scroll observer in JavaScript

### Modifying Animations
Animation timing and easing can be adjusted in CSS custom properties:

```css
:root {
    --transition-fast: 0.2s ease;
    --transition-normal: 0.3s ease;
    --transition-slow: 0.5s ease;
}
```

## License

This website is open source and available under the MIT License, same as the EchoBox application.

---

**Created with love for the EchoBox audio player community**
