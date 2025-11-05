# 🌟 TEN - Tunisian Equality Network

A modern, 3D-enhanced website for the Tunisian Equality Network (TEN) NGO, featuring cutting-edge UI/UX design, smooth animations, and interactive elements.

## ✨ Features

### 🎨 Modern Design
- **3D Card Effects**: Interactive cards with tilt-on-hover effects
- **Gradient Accents**: Beautiful purple-to-pink gradients throughout
- **Glass Morphism**: Frosted glass effects for modern aesthetics
- **Animated Background**: Floating gradient shapes for dynamic feel
- **Particle System**: Animated particles in hero section

### 🚀 Advanced Animations
- **Scroll-triggered animations**: Elements fade and slide in as you scroll
- **Counter animations**: Numbers count up when visible
- **Progress bars**: Animated progress indicators
- **Staggered delays**: Sequential animations for lists
- **3D card tilting**: Cards respond to mouse movement
- **Parallax effects**: Multi-layer scrolling depth

### 📱 Responsive Design
- Fully responsive layout for all devices
- Mobile-first approach
- Hamburger menu for mobile navigation
- Touch-friendly interactive elements
- Optimized for tablets and desktops

### 🎯 User Experience
- **Smooth scrolling**: Buttery-smooth navigation
- **Active nav indicators**: Current section highlighted
- **Scroll-to-top button**: Quick navigation to top
- **Loading animations**: Elegant page load transition
- **Notification system**: Toast notifications for user actions
- **Form validation**: Real-time input validation
- **Cursor glow effect**: Subtle interactive cursor (desktop only)

## 📁 Project Structure

```
NGO/
│
├── index.html          # Main HTML file with semantic structure
├── styles.css          # Modern CSS with 3D effects & animations
├── script.js           # Interactive JavaScript features
└── README.md           # This file
```

## 🎨 Design System

### Color Palette
- **Primary**: #6366f1 (Indigo)
- **Secondary**: #06b6d4 (Cyan)
- **Accent**: #f43f5e (Rose)
- **Success**: #10b981 (Emerald)
- **Dark**: #0f172a (Slate)

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700, 800

### Shadows & Effects
- Multiple shadow levels (sm, md, lg, xl, 3d)
- Glow effects for interactive elements
- Backdrop blur for glass morphism

## 🚀 Getting Started

### Option 1: Direct Open
Simply double-click `index.html` to open in your default browser.

### Option 2: Local Server (Recommended)

**Using Python:**
```bash
python -m http.server 8000
```

**Using Node.js:**
```bash
npx http-server
```

**Using PHP:**
```bash
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📱 Sections

### 1. Navigation
- Fixed header with glass morphism effect
- Smooth scroll navigation
- Active section indicator
- Mobile hamburger menu

### 2. Hero Section
- Animated gradient text
- Floating badge with pulse animation
- Call-to-action buttons with hover effects
- Live statistics display
- Particle background animation
- Scroll indicator

### 3. About Section
- Grid layout with image and text
- 3D card for image
- Floating achievement badges
- Feature list with icons
- Staggered fade-in animations

### 4. Mission Section
- Three-column grid
- Featured card with highlight effect
- Icon wrappers with gradient borders
- 3D hover effects

### 5. Programs Section
- Six program cards
- Numbered cards (01-06)
- Icon badges with shadows
- Feature lists with checkmarks
- "Learn More" links with animations

### 6. Impact Section
- Highlighted statistics
- Animated counters
- Progress bars with fill animations
- Impact metrics cards

### 7. Contact Section
- Two-column layout
- Contact information cards
- Social media links
- Modern form design
- Real-time validation
- Success notifications

### 8. Footer
- Four-column grid
- Newsletter subscription
- Social media links
- Quick navigation
- Gradient accent line

## 🎯 Key Features Explained

### 3D Card Tilt Effect
Cards respond to mouse movement, creating a 3D perspective effect that enhances depth perception.

### Particle Animation
Background particles float and move randomly, adding life to the hero section without being distracting.

### Intersection Observer
Elements animate into view as you scroll, improving engagement and creating a dynamic browsing experience.

### Counter Animation
Numbers count up from 0 to their target value when they enter the viewport, drawing attention to key statistics.

### Progress Bar Animation
Progress bars fill smoothly when visible, providing visual feedback on achievements and metrics.

### Scroll Parallax
Different layers move at different speeds while scrolling, creating depth and visual interest.

### Glass Morphism
Transparent elements with blur effects create a modern, layered aesthetic throughout the site.

## 🛠️ Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary: #6366f1;
    --secondary: #06b6d4;
    --accent: #f43f5e;
    /* ... */
}
```

### Modifying Content
Update text directly in `index.html`. All content is clearly structured with semantic HTML.

### Adding New Sections
Follow the existing pattern:
1. Add HTML structure
2. Apply `.card-3d` class for 3D effects
3. Elements will automatically animate on scroll

### Adjusting Animations
Modify timing and effects in `script.js`:
```javascript
const observerOptions = {
    threshold: 0.1,  // Trigger point
    rootMargin: '0px 0px -100px 0px'  // Offset
};
```

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern features (Grid, Flexbox, Custom Properties, Animations)
- **JavaScript**: Vanilla JS (ES6+)
- **Font Awesome 6**: Icon library
- **Google Fonts**: Poppins typography

## 🎨 CSS Features

- CSS Grid & Flexbox for layouts
- CSS Custom Properties (variables)
- CSS Animations & Keyframes
- Backdrop Filter for glass effects
- CSS Gradients (linear & radial)
- Transform & Perspective for 3D
- Box Shadow for depth
- Transition for smooth effects

## 📜 JavaScript Features

- Intersection Observer API
- Event delegation
- Debouncing for performance
- Dynamic DOM manipulation
- Smooth scrolling
- Animation sequencing
- Form handling
- Notification system

## 🌐 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

**Note**: For best experience, use a modern browser with full CSS3 and ES6+ support.

## 📊 Performance

- Optimized animations (GPU-accelerated)
- Lazy loading for images
- Debounced scroll events
- Minimal dependencies
- Efficient DOM queries
- Smooth 60fps animations

## 🎯 Best Practices

- Semantic HTML5
- BEM-inspired CSS naming
- Mobile-first responsive design
- Progressive enhancement
- Accessible navigation
- SEO-friendly structure
- Clean, commented code

## 🔒 Accessibility

- Semantic HTML elements
- ARIA labels where needed
- Keyboard navigation support
- Focus indicators
- Sufficient color contrast
- Readable font sizes

## 🚀 Future Enhancements

Potential additions:
- Blog section
- Events calendar
- Donation system
- Member portal
- Multi-language support
- Dark mode toggle
- Video backgrounds
- Testimonials slider

## 📞 Support

For questions or support:
- Email: contact@ten-tunisia.org
- Website: [Coming Soon]

## 📄 License

© 2025 Tunisian Equality Network (TEN). All rights reserved.

---

**Built with ❤️ for social equality and justice**

### Credits
- Design & Development: Custom built
- Icons: Font Awesome
- Fonts: Google Fonts (Poppins)
- Inspiration: Modern web design trends 2025

---

## 🎓 Learning Resources

This website demonstrates:
- Modern CSS techniques
- JavaScript animation
- Responsive design patterns
- User experience best practices
- Performance optimization

Feel free to study the code and use it as a learning resource!

---

**Note**: This is a production-ready template. Customize it with your actual content, images, and contact information.