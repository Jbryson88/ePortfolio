# John Bryson - Professional Portfolio

A modern, sophisticated portfolio website showcasing professional experience, technical skills, and iOS development projects.

## 🎨 Design Features

- **Refined Dark Theme** - Professional color palette with gold accents
- **Custom Typography** - Distinctive fonts (Syne, Crimson Pro, JetBrains Mono)
- **Smooth Animations** - Fade-in effects and scroll-based interactions
- **Fully Responsive** - Optimized for desktop, tablet, and mobile
- **Interactive Gallery** - Click images for lightbox view

## 📱 Featured iOS Projects

1. **PrepAI** - AI-powered interview preparation platform
2. **NeuroDecks** - AI flashcard learning application  
3. **WriteCoach** - Personal writing assistant

## 📁 File Structure

```
professional-portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive features
├── images/
│   ├── prepai/        # PrepAI app screenshots (14 images)
│   ├── neurodecks/    # NeuroDecks screenshots (11 images)
│   └── writecoach/    # WriteCoach screenshots (8 images)
└── README.md          # This file
```

## 🚀 Quick Start

### Local Development

1. **Download the portfolio folder**
2. **Open in browser:**
   - Simply double-click `index.html`
   - Or use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     ```
3. **View in browser:** Open `http://localhost:8000`

### Deploy to GitHub Pages

1. **Create a new repository** on GitHub
2. **Upload all files** to the repository
3. **Enable GitHub Pages:**
   - Go to Settings > Pages
   - Source: Deploy from a branch
   - Branch: main / root
   - Save
4. **Your site will be live** at `https://[username].github.io/[repo-name]`

### Deploy to Netlify (Easiest)

1. **Drag and drop** the entire folder to [Netlify Drop](https://app.netlify.com/drop)
2. **Your site is live** immediately with a custom URL
3. **Optional:** Connect to GitHub for automatic updates

## ✏️ Customization

### Update Contact Information

Edit `index.html` and find the contact section:
```html
<a href="mailto:YOUR_EMAIL@example.com" class="contact-link">
<a href="tel:YOUR_PHONE" class="contact-link">
```

### Change Colors

Edit `styles.css` CSS variables at the top:
```css
:root {
    --color-accent-primary: #d4af37;  /* Gold accent */
    --color-bg-primary: #0a0e14;      /* Dark background */
    /* ... more colors ... */
}
```

### Add/Remove Projects

Edit the projects section in `index.html` to add more iOS apps or other work.

### Update Images

Replace images in `/images/[app-name]/` with your own screenshots.

## 📱 Sections Included

- **Hero** - Introduction with name, title, and clearance status
- **About** - Professional summary
- **Skills** - Technical expertise organized by category
- **Experience** - Timeline of DoD work history
- **Projects** - Three featured iOS apps with galleries
- **Education** - Academic credentials
- **Contact** - Multiple contact methods

## 🎯 SEO & Performance

- Semantic HTML5 structure
- Optimized images
- Fast loading times
- Mobile-first responsive design
- Accessible navigation

## 📄 License

This portfolio template is free to use and modify for personal use.

## 📧 Contact

John Bryson  
Email: John.bryson710@gmail.com  
Phone: (719) 374-2074  
Location: Rockland, MA

---

**Software Engineer · iOS Developer · U.S. Army Veteran** ✨
