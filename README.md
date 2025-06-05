# Modern Landing Page

A clean, responsive landing page template built with HTML, CSS, and Bootstrap 5. This template includes all the essential sections needed for a modern landing page: hero section, features, about us, contact form, and a footer.

## Features

- 📱 Fully responsive design
- 🎨 Modern and clean UI
- 🚀 Built with Bootstrap 5
- 💨 Smooth animations
- 📦 No build process required
- 🎯 SEO friendly
- 🖼️ Hero section with background image
- 📝 Contact form
- 🎉 Font Awesome icons included

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser
3. Customize the content and styling to match your needs

## Customization

### Changing Colors

The main colors are defined as CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #007bff;
    --secondary-color: #6c757d;
    --dark-color: #343a40;
    --light-color: #f8f9fa;
}
```

### Changing the Hero Image

To change the hero background image, modify the following CSS in `css/style.css`:

```css
.hero {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
                url('your-image-url-here') no-repeat center center/cover;
}
```

### Adding New Sections

The template uses Bootstrap's grid system. To add new sections, follow the existing pattern:

```html
<section id="your-section" class="py-5">
    <div class="container">
        <!-- Your content here -->
    </div>
</section>
```

## Dependencies

- Bootstrap 5.3.2
- Font Awesome 6.5.1

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This template is free to use for both personal and commercial projects. Attribution is appreciated but not required.

## Contributing

Feel free to submit issues and enhancement requests! 