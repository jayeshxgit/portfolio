# Portfolio Website - Netflix UI + Spotify UX

A modern, responsive portfolio website that combines Netflix's sleek dark UI with Spotify's smooth UX, built with pure HTML and CSS.

## 🎨 Design Features

### Netflix UI Elements
- **Dark Theme**: Deep blacks and dark grays with Netflix's signature red (#E50914)
- **Card-Based Layout**: Project cards with hover effects and overlays
- **Hero Section**: Cinematic hero section with gradient backgrounds
- **Modern Typography**: Clean, readable fonts with gradient text effects
- **Smooth Animations**: CSS animations for enhanced user experience

### Spotify UX Elements
- **Sidebar Navigation**: Fixed left sidebar with Spotify's green (#1DB954)
- **Smooth Interactions**: Hover effects and active states
- **Playlist-Style Organization**: Content organized in sections
- **Modern Iconography**: Font Awesome icons throughout
- **Responsive Design**: Works seamlessly on all devices

## 🚀 Features

- **Pure HTML & CSS**: No JavaScript frameworks required
- **Responsive Design**: Mobile-first approach with breakpoints
- **Smooth Scrolling**: Navigate between sections smoothly
- **Background Animation**: Floating particles for visual appeal
- **Accessibility**: Focus styles and reduced motion support
- **Modern CSS**: CSS Grid, Flexbox, and CSS Variables

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # All styling (Netflix + Spotify theme)
└── README.md          # This file
```

## 🎯 Sections

1. **Hero Section**: Welcome message with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Projects Section**: Featured projects with Netflix-style cards
4. **Skills Section**: Technical skills organized by category
5. **Contact Section**: Contact information and methods

## 🛠️ Customization

### Colors
Edit the CSS variables in `:root` to change the color scheme:

```css
:root {
    --netflix-red: #E50914;
    --spotify-green: #1DB954;
    --primary-bg: #0D1117;
    --text-primary: #F0F6FC;
    /* ... more variables */
}
```

### Content
Update the HTML content in `index.html`:

- Change name, title, and description in the hero section
- Update project information and links
- Modify skills and experience details
- Add your contact information

### Styling
Customize the appearance by modifying `style.css`:

- Adjust animations and transitions
- Change layout and spacing
- Update typography and font sizes
- Modify responsive breakpoints

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: 480px to 767px
- **Small Mobile**: Below 480px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🚀 Getting Started

1. **Clone or download** the project files
2. **Open** `index.html` in your browser
3. **Customize** the content and styling to match your needs
4. **Deploy** to your preferred hosting platform

## 💡 Tips for Customization

### Adding Your Photo
Replace the profile placeholder in the hero section:
```html
<div class="profile-placeholder">
    <img src="your-photo.jpg" alt="Your Name">
</div>
```

### Adding Project Images
Update project cards with actual images:
```html
<div class="project-placeholder">
    <img src="project-screenshot.jpg" alt="Project Name">
</div>
```

### Social Media Links
Update the social links in the sidebar:
```html
<a href="https://github.com/yourusername" class="social-link">
    <i class="fab fa-github"></i>
</a>
```

### Adding More Sections
Follow the existing pattern to add new sections:
```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <!-- Your content here -->
    </div>
</section>
```

## 🎨 Animation Details

- **Fade In Up**: Hero content animates from bottom to top
- **Floating Effect**: Profile image has a subtle floating animation
- **Particle Background**: Animated particles float upward
- **Hover Effects**: Cards lift and glow on hover
- **Smooth Transitions**: All interactions are smooth and responsive

## 📊 Performance

- **Lightweight**: Pure CSS with no external dependencies (except fonts and icons)
- **Fast Loading**: Optimized CSS with efficient selectors
- **Smooth Animations**: Hardware-accelerated CSS animations
- **Minimal HTTP Requests**: Single HTML and CSS file

## 🔧 Accessibility Features

- **Focus Styles**: Keyboard navigation support
- **High Contrast Mode**: Adapts to user preferences
- **Reduced Motion**: Respects user's motion preferences
- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Alt Text**: Placeholder for image descriptions

## 🎭 Theme Inspiration

This portfolio combines the best of both worlds:

- **Netflix**: Dark, premium feel with dramatic hover effects
- **Spotify**: Clean navigation and smooth user interactions
- **Modern Web**: Contemporary design patterns and animations

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to customize and improve this portfolio template! Share your modifications and enhancements with the community.

---

**Built with ❤️ using pure HTML and CSS**