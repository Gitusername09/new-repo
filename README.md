# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first approach.

## Features

- 🎨 **Modern Design**: Clean, professional layout with beautiful gradients and shadows
- 📱 **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- ✨ **Smooth Animations**: Scroll-triggered animations and hover effects
- 🧭 **Smooth Navigation**: One-page design with smooth scrolling between sections
- 📊 **Interactive Elements**: Animated counters, progress indicators, and form validation
- 🎭 **Dynamic Effects**: Parallax scrolling, tilt effects, and typing animations
- 📬 **Contact Form**: Functional contact form with validation
- ♿ **Accessible**: Built with accessibility best practices

## Sections

1. **Hero Section**: Introduction with call-to-action buttons
2. **About**: Personal information and statistics
3. **Skills**: Technical skills organized by category
4. **Projects**: Featured projects with descriptions and links
5. **Contact**: Contact information and contact form
6. **Footer**: Social links and copyright

## Getting Started

### Prerequisites

- A modern web browser
- A text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start customizing with your own content

### Customization

#### Personal Information

Edit the following in `index.html`:

```html
<!-- Update your name -->
<span class="highlight">Your Name</span>

<!-- Update your title/role -->
<p class="hero-subtitle">Full Stack Developer & Creative Problem Solver</p>

<!-- Update your description -->
<p class="hero-description">
    I craft digital experiences that combine beautiful design with robust functionality.
    Passionate about clean code, user experience, and innovative solutions.
</p>

<!-- Update contact information -->
<p>your.email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>Your City, Country</p>
```

#### Skills

Update the skills in the Skills section:

```html
<div class="skill-items">
    <span class="skill-item">Your Skill</span>
    <span class="skill-item">Another Skill</span>
    <!-- Add more skills as needed -->
</div>
```

#### Projects

Replace the example projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

#### Colors and Styling

Customize the color scheme in `styles.css`:

```css
:root {
    --primary-color: #6366f1;     /* Main theme color */
    --primary-dark: #4f46e5;      /* Darker variant */
    --secondary-color: #f59e0b;   /* Accent color */
    /* Update other colors as needed */
}
```

#### Social Links

Update social media links in the footer:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="your-linkedin-url" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <!-- Add more social links as needed -->
</div>
```

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js          # JavaScript functionality
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

The website is optimized for performance with:
- Efficient CSS animations
- Debounced scroll events
- Optimized images and icons
- Minimal external dependencies

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main` or `master`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. Connect your GitHub repository to Netlify
2. Deploy automatically on every push
3. Custom domain support available

### Vercel

1. Import your GitHub repository
2. Automatic deployments
3. Instant domain and HTTPS

## Customization Tips

1. **Images**: Replace the Font Awesome icons with actual project screenshots
2. **Content**: Update all placeholder text with your actual information
3. **Animations**: Adjust animation timing in `script.js` and `styles.css`
4. **Layout**: Modify the grid layouts to fit your content
5. **Colors**: Use tools like [Coolors](https://coolors.co/) to generate color palettes

## Optional Features

The codebase includes several optional features you can enable:

### Dark Mode Toggle
Uncomment this line in `script.js`:
```javascript
createThemeToggle(); // Uncomment to enable theme toggle
```

### Additional Animations
Add more CSS animations by extending the existing keyframes.

## Contributing

Feel free to fork this project and submit pull requests for improvements!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Happy coding!** 🚀