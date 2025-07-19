# Personal Portfolio Website

A modern, responsive portfolio website built with vanilla HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and experience as a CS student.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Skill Visualization**: Animated skill bars and technology tags
- **Project Showcase**: Beautiful project cards with technology tags
- **Timeline Experience**: Visual timeline for work experience
- **Loading Animation**: Smooth page loading experience

## Sections

1. **Hero Section**: Eye-catching introduction with animated text
2. **About**: Personal information and statistics
3. **Education**: Academic background
4. **Experience**: Work history with timeline layout
5. **Projects**: Portfolio of projects with descriptions and links
6. **Skills**: Programming languages and technologies
7. **Contact**: Contact form and social links

## Customization Guide

### Personal Information

1. **Update your name and title** in the HTML file:
   ```html
   <title>Your Name - CS Student Portfolio</title>
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   ```

2. **Modify the about section** with your personal information:
   ```html
   <p>Your personal description here...</p>
   ```

3. **Update contact information**:
   ```html
   <a href="mailto:your.email@example.com">your.email@example.com</a>
   ```

### Projects

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-code"></i> <!-- Change icon as needed -->
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="your-live-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### Skills

Update your skills in the skills section:

1. **Programming Languages**: Modify the skill bars and percentages
2. **Technologies**: Add or remove technology tags

### Experience

Update the timeline with your work experience:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <p class="company">Company Name</p>
        <p class="duration">Duration</p>
        <ul>
            <li>Your responsibility 1</li>
            <li>Your responsibility 2</li>
        </ul>
    </div>
</div>
```

### Colors and Styling

The website uses a modern color scheme with gradients. You can customize colors in the CSS file:

- Primary blue: `#2563eb`
- Gradient colors: `#667eea` to `#764ba2`
- Accent yellow: `#fbbf24`

## Adding Images

1. Create an `images` folder in your project
2. Add your profile picture and project screenshots
3. Update the HTML to reference your images:

```html
<img src="images/your-photo.jpg" alt="Your Name" class="profile-image">
```

## Deployment

### GitHub Pages (Recommended for students)

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly

### Vercel

1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Automatic deployments on every push

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Lazy loading for images
- Optimized animations
- Smooth scrolling
- Responsive images
- Minimal JavaScript footprint

## Customization Tips

1. **Keep it simple**: Don't overload with too many animations
2. **Update regularly**: Keep your projects and experience current
3. **Test on mobile**: Always test on different screen sizes
4. **Optimize images**: Compress images for faster loading
5. **Add analytics**: Consider adding Google Analytics to track visitors

## File Structure

```
personal-portfolio/
├── personal-portfolio.html
├── style.css
├── script.js
├── images/
│   ├── profile.jpg
│   └── projects/
└── README.md
```

## Credits

- Fonts: [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts
- Icons: [Font Awesome](https://fontawesome.com/)
- Design inspiration: Modern web design principles

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🚀**

Feel free to customize this portfolio to match your personal style and showcase your unique skills and projects.
