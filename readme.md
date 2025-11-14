# 🚀 Atul Bharadwaj - Portfolio Website

A stunning, modern portfolio website showcasing professional experience, skills, projects, and publications with beautiful animations and interactive elements.

## ✨ Features

### 🎨 Design & UI
- **Modern Gradient Design** - Beautiful purple/pink gradient theme
- **Smooth Animations** - Fade-in, slide, scale, and rotation effects
- **Particle System** - Animated particles in hero section
- **Glitch Text Effect** - Eye-catching hero title animation
- **Glassmorphism** - Modern frosted glass effects
- **Responsive Design** - Perfect on all devices (desktop, tablet, mobile)

### ⚡ Interactive Elements
- **Smooth Scrolling** - Buttery smooth navigation
- **Animated Counters** - Stats count up on scroll
- **Skill Bars** - Progress bars animate when visible
- **Hover Effects** - 3D transforms and shadows
- **Cursor Trail** - Custom cursor effect (desktop only)
- **Back to Top Button** - Quick navigation to top
- **Mobile Menu** - Hamburger menu for mobile devices

### 📱 Sections
1. **Hero** - Eye-catching intro with social links
2. **About** - Bio, education, and stats
3. **Skills** - Comprehensive skill showcase with categories
4. **Experience** - Professional timeline with details
5. **Projects** - Featured project cards
6. **Publications** - Research papers and publications
7. **Contact** - Contact form and information

### 🎯 Special Features
- **Active Nav Links** - Highlights current section while scrolling
- **Parallax Effects** - Smooth parallax scrolling
- **Lazy Loading** - Optimized performance
- **Easter Egg** - Konami code surprise! (↑↑↓↓←→←→BA)
- **Console Messages** - Fun messages for developers

## 🚀 Quick Start

### Option 1: Open Directly (Easiest)
1. Simply open `index.html` in your web browser
2. That's it! 🎉

### Option 2: Local Server (Recommended for Development)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Then open: http://localhost:8000
```

### Option 3: VS Code Live Server
1. Install "Live Server" extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

## 🌐 Deploy to Web (FREE)

### Deploy to GitHub Pages (Recommended)
```bash
# 1. Create a new repository on GitHub
# 2. Push your code
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main

# 3. Enable GitHub Pages
# Go to Settings → Pages → Source → main branch → Save
# Your site will be live at: https://YOUR_USERNAME.github.io/YOUR_REPO/
```

### Deploy to Netlify
1. Go to [netlify.com](https://www.netlify.com/)
2. Drag and drop the `biopage` folder
3. Your site is live in seconds!

### Deploy to Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd biopage
vercel

# Follow the prompts - done!
```

## 🎨 Customization

### Update Personal Information

**1. Contact Details** (`index.html`):
```html
<!-- Update these lines -->
<a href="mailto:YOUR_EMAIL@gmail.com">
<a href="tel:+1YOURNUMBER">
<a href="https://www.linkedin.com/in/YOUR_LINKEDIN">
<a href="https://github.com/YOUR_GITHUB">
```

**2. Colors** (`styles.css`):
```css
:root {
    --primary-color: #6366f1;    /* Change to your color */
    --secondary-color: #8b5cf6;  /* Change to your color */
    --accent-color: #ec4899;     /* Change to your color */
}
```

**3. Content**:
- Edit `index.html` to update:
  - Hero text
  - About section
  - Skills
  - Experience
  - Projects
  - Publications

### Add Your Photo
```html
<!-- In the hero section or about section, add: -->
<img src="your-photo.jpg" alt="Your Name" class="profile-photo">
```

### Add More Projects
```html
<!-- Copy and paste a project-card div in the projects section -->
<div class="project-card">
    <!-- Update content -->
</div>
```

## 📂 File Structure
```
biopage/
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # Interactive features
└── README.md           # This file
```

## 🎯 Browser Support
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🔧 Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (Vanilla)** - No frameworks needed!
- **Font Awesome** - Icons
- **Google Fonts** - Typography (System fonts for speed)

## 💡 Tips

### Performance
- The site is already optimized for speed
- All animations use CSS transforms (GPU accelerated)
- No external dependencies except Font Awesome

### SEO
- Add meta tags in `<head>`:
```html
<meta name="description" content="Your description">
<meta name="keywords" content="your, keywords">
<meta property="og:image" content="your-preview-image.jpg">
```

### Analytics
Add Google Analytics before `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_ID');
</script>
```

## 🐛 Troubleshooting

**Animations not working?**
- Make sure JavaScript is enabled
- Check browser console for errors

**Responsive issues?**
- Clear browser cache
- Test in different browsers

**Contact form not working?**
- Currently uses `mailto:` link
- For a backend form, use Formspree, Netlify Forms, or similar

## 📝 License
Feel free to use this template for your own portfolio!

## 🤝 Contributing
Found a bug or want to add a feature? Feel free to open an issue or PR!

## 📧 Contact
Built by Atul Bharadwaj
- Email: atulnmbharadwaj@gmail.com
- LinkedIn: [linkedin.com/in/atulnm2002](https://www.linkedin.com/in/atulnm2002)
- GitHub: [github.com/atulnm2002](https://github.com/atulnm2002)

---

**⭐ If you found this helpful, please star the repository!**

**Made with ❤️ and lots of ☕**

