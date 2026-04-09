# Portfolio Images - Usage Guide

This folder contains all screenshots for your iOS applications, organized and ready to drop into your website repository.

## Folder Structure

```
portfolio-images/
├── writecoach/     (9 screenshots)
├── neurodecks/     (11 screenshots)
└── prepai/         (15 screenshots)
```

**Total: 35 professional screenshots**

---

## How to Use

### Quick Setup

1. **Upload to GitHub:**
   - Drag the entire `portfolio-images` folder into your repository
   - Or use: `git add portfolio-images/`

2. **Update Image Paths:**
   - If your HTML/Markdown is in the root: `./portfolio-images/writecoach/01-welcome-ipad.png`
   - If it's in a subfolder: `../portfolio-images/writecoach/01-welcome-ipad.png`
   - Absolute path: `/portfolio-images/writecoach/01-welcome-ipad.png`

3. **Verify:**
   - Push to GitHub and enable GitHub Pages
   - Images will automatically be served

---

## Image Catalog

### WriteCoach (9 images)

**iPad Screenshots:**
- `01-welcome-ipad.png` - Welcome/onboarding screen
- `02-rewrite-ipad.png` - Main rewrite interface with tone options
- `03-tools-ipad.png` - Professional tools menu
- `04-settings-ipad.png` - Settings and subscription screen

**iPhone Screenshots:**
- `05-welcome-iphone.png` - Welcome screen (mobile)
- `06-subscription-iphone.png` - Subscription options
- `07-settings-iphone.png` - Settings with AI provider selection
- `08-rewrite-iphone.png` - Rewrite interface (mobile)
- `09-tools-iphone.png` - Tools menu (mobile)

**Best for showcasing:**
- 02 - Main feature (rewriting with tones)
- 03 - Professional tools
- 06 - Monetization/subscription

---

### Neurodecks (11 images)

**iPad Screenshots:**
- `01-home-ipad.png` - Home dashboard with study stats
- `02-deck-creation-ipad.png` - Create new deck interface
- `03-card-creation-ipad.png` - Manual card creation
- `04-settings-ipad.png` - Settings with AI providers
- `05-subscription-ipad.png` - Premium subscription details

**iPhone Screenshots:**
- `06-welcome-iphone.png` - Welcome/onboarding
- `07-home-iphone.png` - Home dashboard (mobile)
- `08-deck-creation-iphone.png` - Deck creation (mobile)
- `09-card-creation-iphone.png` - Card creation (mobile)
- `10-settings-iphone.png` - Settings with provider picker
- `11-subscription-iphone.png` - Subscription screen

**Best for showcasing:**
- 01 - Dashboard with study stats
- 03 - Card creation feature
- 05 - Premium features list

---

### PrepAI (15 images)

**iPad Screenshots:**
- `01-welcome-ipad.png` - Welcome screen
- `02-focus-area-ipad.png` - Career field selection
- `03-home-ipad.png` - Home dashboard
- `04-practice-ipad.png` - Interview type selection
- `05-study-ipad.png` - Study mode with flashcards
- `06-settings-ipad.png` - Settings screen
- `07-subscription-ipad.png` - Subscription details

**iPhone Screenshots:**
- `08-welcome-iphone.png` - Welcome (mobile)
- `09-features-iphone.png` - Feature overview
- `10-focus-area-iphone.png` - Career selection (mobile)
- `11-home-iphone.png` - Home dashboard (mobile)
- `12-practice-iphone.png` - Interview types (mobile)
- `13-study-iphone.png` - Study mode (mobile)
- `14-subscription-iphone.png` - Annual subscription
- `15-subscription-monthly-iphone.png` - Monthly subscription

**Best for showcasing:**
- 02 - Career field customization
- 04 - Interview types (unique feature)
- 07 - Premium features

---

## Usage Examples

### HTML
```html
<!-- Single image -->
<img src="./portfolio-images/writecoach/02-rewrite-ipad.png" 
     alt="WriteCoach Rewrite Interface" 
     style="max-width: 100%; height: auto;">

<!-- Gallery -->
<div class="gallery">
    <img src="./portfolio-images/writecoach/01-welcome-ipad.png" alt="Welcome">
    <img src="./portfolio-images/writecoach/02-rewrite-ipad.png" alt="Rewrite">
    <img src="./portfolio-images/writecoach/03-tools-ipad.png" alt="Tools">
</div>
```

### Markdown
```markdown
![WriteCoach Welcome](./portfolio-images/writecoach/01-welcome-ipad.png)

<!-- With sizing -->
<img src="./portfolio-images/writecoach/02-rewrite-ipad.png" width="300" alt="Rewrite Interface">
```

### CSS Optimization
```css
/* Lazy loading */
img {
    loading: lazy;
}

/* Responsive images */
img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

/* Hover effect */
img:hover {
    transform: scale(1.05);
    transition: transform 0.3s;
}
```

---

## Recommended Display Order

### For Portfolio Hero Section
Show 3-4 hero images that best represent each app:
- WriteCoach: `02-rewrite-ipad.png`
- Neurodecks: `01-home-ipad.png`
- PrepAI: `04-practice-ipad.png`

### For Detailed App Pages
Use 6-9 images showing:
1. Welcome/onboarding (user's first impression)
2. Main feature (core functionality)
3. Settings (customization/AI providers)
4. Premium/subscription (monetization)
5. iPhone variant (responsive design)

### For GitHub README
Use iPad screenshots primarily - they show more detail in thumbnails.

---

## File Size & Performance

All images are optimized PNG files:
- Average size: ~100-150 KB each
- Total folder size: ~5 MB
- Already optimized for web (no further compression needed)

**Performance tips:**
- Use `loading="lazy"` attribute for images below the fold
- Consider WebP format for even smaller sizes (optional)
- GitHub Pages serves images efficiently by default

---

## Troubleshooting

**Images not showing?**
1. Check file path (case-sensitive on Linux servers)
2. Verify folder uploaded to repo
3. Check GitHub Pages is enabled
4. Try absolute path: `/portfolio-images/...`

**Images too large?**
- They're already optimized, but you can reduce display size with CSS:
  ```css
  img { max-width: 600px; }
  ```

**Need different formats?**
These are all PNG (best quality). Convert to WebP for smaller sizes:
```bash
# Using imagemagick
convert input.png output.webp
```

---

## Next Steps

1. ✅ Upload `portfolio-images/` folder to your repo
2. ✅ Update image paths in your HTML/Markdown
3. ✅ Push to GitHub
4. ✅ Enable GitHub Pages
5. ✅ Verify images load correctly

**Questions?** The images are production-ready - just drop them in and update your paths!
