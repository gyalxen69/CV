# 💼 Professional CV Website

A modern, responsive, and interactive CV/Resume webpage built with pure HTML, CSS, and JavaScript. Features a stunning gradient design, smooth animations, and an elegant user interface.

## ✨ Features

- 🎨 **Modern Design**: Beautiful gradient header with animated particles
- 📱 **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- ✨ **Interactive Animations**: Scroll animations, hover effects, and typing effects
- 🖼️ **Profile Photo Section**: Easy-to-replace profile image with placeholder
- 📊 **Complete CV Sections**:
  - About Me
  - Technical Skills (categorized)
  - Work Experience (timeline view)
  - Featured Projects
  - Education & Certifications
- 🔗 **Social Media Integration**: Links to GitHub, LinkedIn, Twitter, and personal website
- 📋 **Click-to-Copy**: Contact information can be copied with a single click
- 💾 **Download CV**: Print-friendly design with download button
- 🎯 **No Dependencies**: Pure vanilla JavaScript, no frameworks required

## 🚀 Quick Start

### Option 1: Open Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/cv-website.git
   ```
2. Navigate to the project folder:
   ```bash
   cd cv-website
   ```
3. Open `index.html` in your browser

### Option 2: Use Live Server
1. Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Deploy to GitHub Pages
1. Go to your repository settings
2. Navigate to **Pages** section
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/cv-website/`

## 📁 Project Structure

```
cv-website/
│
├── index.html          # Main HTML structure
├── styles.css          # All styling and animations
├── script.js           # Interactive features and animations
├── imgs
  ├── profile.jpg         # Your profile photo (add your own)
└── README.md           # Project documentation
```

## 🎨 Customization

### 1. Personal Information
Edit the following sections in `index.html`:

- **Name and Title**: Lines 22-24
- **Contact Information**: Lines 28-38
- **Social Links**: Lines 40-44
- **About Me**: Lines 55-59
- **Skills**: Lines 68-117
- **Work Experience**: Lines 126-175
- **Projects**: Lines 184-241
- **Education**: Lines 250-265

### 2. Profile Photo
- Replace `profile.jpeg` with your own image
- Recommended size: 500x500px or larger
- Supported formats: JPG, PNG, WebP

### 3. Color Scheme
Modify the CSS variables in `styles.css` (lines 7-16):

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    --gradient-start: #667eea;
    --gradient-end: #764ba2;
}
```

### 4. Font
Change the font family in `styles.css` (line 19):

```css
font-family: 'Your Font', sans-serif;
```

## 🌟 Features Breakdown

### Interactive Elements
- **Typing Animation**: Tagline types out on page load
- **Scroll Animations**: Sections fade in as you scroll
- **Timeline Animation**: Work experience appears with staggered timing
- **Hover Effects**: Cards, buttons, and links respond to mouse interaction
- **Particle Effect**: Animated particles in the header
- **Parallax Scrolling**: Header moves with scroll for depth

### Responsive Design
- **Desktop**: Full layout with all features
- **Tablet**: Adjusted grid and spacing
- **Mobile**: Single column, optimized touch targets

### Browser Compatibility
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)

## 📥 Download CV Feature

The "Download CV" button triggers the browser's print dialog, allowing users to:
- Save as PDF
- Print physical copy
- Customize print settings

The print styles are optimized to remove unnecessary elements and ensure a clean, professional output.

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Animations, Custom Properties
- **JavaScript**: ES6+, Intersection Observer API, DOM Manipulation
- **Font Awesome**: Icons (via CDN)

## 📱 Social Media Links

Update your social media URLs in `index.html` (lines 40-44):

```html
<a href="https://github.com/yourusername" class="social-link">
<a href="https://linkedin.com/in/yourusername" class="social-link">
<a href="https://toyourwhatsapp" class="social-link">
```

## 🎯 Use Cases

- Personal portfolio website
- Online resume/CV
- Professional introduction page
- Job application showcase
- Networking tool

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is [MIT](LICENSE) licensed. Feel free to use it for your own CV!

## 👤 Author

**Gelchhen Sherpa**

- GitHub: [@gyalxen69](https://github.com/gyalxen69)
- LinkedIn: [@Gelchhen Sherpa](https://www.linkedin.com/in/gelchhen-sherpa-762594230)
---

**Note**: Remember to replace placeholder information with your actual details before deploying!

## 🔮 Future Enhancements

- [ ] Dark mode toggle
- [ ] Multi-language support
- [ ] Blog section
- [ ] Contact form with backend integration
- [ ] Analytics integration
- [ ] SEO optimization
- [ ] Performance optimization (lazy loading)

---

Made with ❤️ and ☕
