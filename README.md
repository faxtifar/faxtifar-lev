# Faxtifar - Developer Portfolio

A stunning, modern portfolio website for **Faxtifar** - a full-stack developer showcasing skills in HTML, CSS, JavaScript, and Python.

## ✨ Features

- **Animated Hero Section**: Eye-catching introduction with gradient text and smooth animations
- **Falling Particles Background**: Dynamic particle animation system that creates depth and visual interest
- **Skills Showcase**: Interactive skill cards with hover effects and floating animations
- **Responsive Design**: Fully responsive layout that works on all devices
- **Smooth Scrolling**: Elegant navigation with smooth scroll behavior
- **Modern Aesthetics**: Dark theme with blue and purple gradient accents
- **Performance Optimized**: Lightweight and fast-loading

## 🎨 Design Highlights

- **Color Scheme**: Dark background with blue (#60a5fa) and purple (#a78bfa) gradients
- **Animations**: 
  - Falling particle system in background
  - Fade-in animations on scroll
  - Hover effects on skill cards
  - Floating icon animations
  - Shine effect on cards
- **Typography**: Modern sans-serif with bold headings and clear hierarchy
- **Icons**: Font Awesome icons for programming languages

## 🛠️ Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Advanced animations and gradients
- **JavaScript**: Interactive features and particle system
- **Tailwind CSS**: Utility-first styling (via CDN)
- **Font Awesome**: Icon library

## 📱 Sections

1. **Navigation**: Sticky navbar with smooth scrolling links
2. **Hero Section**: Main introduction with call-to-action button
3. **Skills Section**: Four skill cards (HTML, CSS, JavaScript, Python)
4. **About Section**: Personal introduction with profile image
5. **Contact Section**: Call-to-action for getting in touch
6. **Footer**: Copyright and credits

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/faxtifar/faxtifar-portfolio.git
cd faxtifar-portfolio
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

3. Visit `http://localhost:8000` in your browser

### Deploy to GitHub Pages

1. Push the repository to GitHub
2. Go to repository Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://yourusername.github.io/faxtifar-portfolio/`

## 📝 Customization

### Change Colors
Edit the CSS gradient values in the `<style>` section:
- Primary color: `#60a5fa` (blue)
- Secondary color: `#a78bfa` (purple)
- Accent color: `#ec4899` (pink)

### Update Content
- Edit the text in each section
- Replace the profile image URL in the About section
- Update social links in the Contact section

### Add More Skills
Add new skill cards by duplicating the skill-card div:
```html
<div class="skill-card fade-in">
    <div class="skill-icon">
        <i class="fab fa-[icon-name]" style="color: #color;"></i>
    </div>
    <div class="skill-name">Skill Name</div>
    <div class="skill-description">Description here</div>
</div>
```

## 🎯 Performance

- Lightweight: No heavy frameworks or dependencies
- Fast loading: Optimized CSS and minimal JavaScript
- Smooth animations: GPU-accelerated transforms
- SEO friendly: Semantic HTML structure

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Faxtifar** - Full Stack Developer

---

Made with ❤️ and code

---
&copy; 2026 Faxtifar. All rights reserved.
