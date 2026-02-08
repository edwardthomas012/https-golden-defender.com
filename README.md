# GOLDEN DEFENDER Website

A modern, polished arcade restoration website with retro black and gold aesthetics.

## 🎮 Features

- **Retro Arcade Theme**: Black and gold color scheme with neon accents
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Image Carousel**: Polished lightbox with keyboard navigation
- **Smooth Animations**: Entrance animations, hover effects, and transitions
- **Organized Structure**: 20+ pages for complete restoration documentation

## 📁 File Structure

```
golden-defender-website/
├── index.html              # Home page
├── bezel.html             # Bezel gallery (template for other galleries)
├── controls.html          # Controls gallery
├── marquee.html           # Marquee gallery
├── boards.html            # Boards gallery
├── monitor.html           # Monitor gallery
├── coin-door.html         # Coin door gallery
├── full-photos.html       # All photos gallery
├── beginnings.html        # Restoration beginning
├── history.html           # Game history
├── parts.html             # Parts list
├── paint.html             # Paint process
├── inspection.html        # Inspection details
├── creator.html           # About the creator
├── extras.html            # Extra content
├── tribute.html           # Tribute page
├── poem.html              # Poetry page
├── story.html             # Story page
├── songs.html             # Music/songs
├── sounds.html            # Sound effects
├── video.html             # Videos
├── enemies.html           # Game enemies info
├── schematics.html        # Technical schematics
├── contact.html           # Contact form
├── faq.html               # FAQ page
├── styles/
│   ├── main.css           # Main stylesheet
│   └── gallery.css        # Gallery/carousel styles
├── js/
│   └── main.js            # JavaScript functionality
└── images/                # All images organized by category
    ├── bezel/
    ├── controls/
    ├── marquee/
    └── ... (etc)
```

## 🚀 How to Use

### 1. Add Your Images

Place your photos in the appropriate folders:
- `images/bezel/` - Bezel photos (bezel-1.jpg, bezel-2.jpg, etc.)
- `images/controls/` - Control panel photos
- `images/marquee/` - Marquee photos
- And so on for each category

**Naming Convention**: Use descriptive names like `bezel-1.jpg`, `controls-front.jpg`, etc.

### 2. Update Photo Counts

In each gallery HTML file, update the photo count in the header:
```html
<p class="photo-count" id="photoCount">9 Photos</p>
```

And add/remove photo items in the gallery grid as needed.

### 3. Customize Content

- Edit the page titles and descriptions in each HTML file
- Update the footer information in `index.html` (it's shared across pages)
- Modify color schemes in `styles/main.css` (CSS variables at the top)

### 4. Upload to GitHub Pages

1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings → Pages
4. Set Source to "main" branch
5. Your site will be live at: `yourusername.github.io/repository-name`

## 🎨 Customization

### Colors

Edit CSS variables in `styles/main.css`:

```css
:root {
    --gold-primary: #FFD700;      /* Main gold color */
    --black-arcade: #0a0015;      /* Background color */
    --cyan-electric: #00ffff;     /* Accent color */
    /* Modify as needed */
}
```

### Fonts

Current fonts:
- Display: 'Orbitron' (retro sci-fi)
- Body: 'Rajdhani' (clean, modern)

To change, update the Google Fonts link and CSS variables.

### Navigation

Edit the navigation menu in each HTML file to add/remove pages.

## 📸 Gallery/Carousel Features

### How It Works

1. Click any photo to open the lightbox carousel
2. Use arrow keys or navigation buttons to browse
3. Press ESC to close
4. Click outside the image to close
5. Displays photo counter (e.g., "3 / 9")

### Adding More Photos

In any gallery page (e.g., `bezel.html`):

```html
<div class="photo-item">
    <span class="photo-number">#10</span>
    <img src="images/bezel/bezel-10.jpg" alt="Bezel Photo 10">
</div>
```

The JavaScript automatically detects all images and adds them to the carousel!

## 🌐 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## 📱 Mobile Responsive

- Mobile menu toggle for small screens
- Touch-friendly carousel navigation
- Optimized image sizes
- Stacked layouts on mobile

## 🛠️ Technical Notes

### No Dependencies

This website uses:
- Pure HTML5
- Vanilla CSS3
- Vanilla JavaScript
- Google Fonts (only external dependency)

No frameworks, no build process - just upload and go!

### Performance

- Lazy loading images
- CSS animations (GPU accelerated)
- Minimal JavaScript
- Optimized for fast loading

## 📝 Page Templates

### Gallery Page Template

Use `bezel.html` as a template for creating new gallery pages:

1. Copy `bezel.html`
2. Rename to your page (e.g., `new-section.html`)
3. Update the title, header text, and photo count
4. Update image paths in the photo grid
5. Add to navigation menu

### Content Page Template

For non-gallery pages (like story, history, etc.), you can create a simpler layout without the carousel.

## 🎯 Tips for Best Results

1. **Image Sizes**: Optimize images to ~1200px width for faster loading
2. **Consistent Naming**: Keep file names lowercase with hyphens
3. **Alt Text**: Always include descriptive alt text for accessibility
4. **Test Locally**: Open `index.html` in your browser before uploading
5. **Backup**: Keep a local copy of all your images

## 🔧 Troubleshooting

**Images not showing?**
- Check file paths match exactly (case-sensitive)
- Ensure images are in correct folders
- Check browser console for errors

**Carousel not working?**
- Ensure `js/main.js` is loaded
- Check browser console for JavaScript errors
- Make sure images have the class "photo-item"

**Mobile menu not opening?**
- Clear browser cache
- Check JavaScript console
- Ensure viewport meta tag is present

## 📞 Support

For questions or issues:
- Check the FAQ page
- Review the contact page
- Inspect browser console for errors

## 📄 License

Free to use for personal projects. Modify as needed!

---

**Built with ❤️ for arcade restoration enthusiasts**

Enjoy your GOLDEN DEFENDER website! 🎮✨
