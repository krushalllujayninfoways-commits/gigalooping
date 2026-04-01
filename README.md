# Gigalooping - Professional 3D Website

A modern, professional website with interactive 3D elements using Three.js.

## Features

✨ **Interactive 3D Hero Section**
- Rotating 3D objects (cube, sphere, torus)
- Dynamic lighting effects
- Smooth animations

📱 **Fully Responsive Design**
- Mobile-friendly layout
- Touch-optimized navigation
- Scales beautifully on all devices

🎨 **Modern UI/UX**
- Gradient color scheme (Blue & Cyan)
- Smooth transitions and hover effects
- Glass-morphism navigation bar
- Professional typography

🚀 **Performance Optimized**
- Efficient Three.js rendering
- Optimized asset loading
- Smooth 60fps animations

## Getting Started

### Prerequisites
- Node.js (optional)
- Modern web browser

### Installation

```bash
# Clone the repository
git clone https://github.com/krushalllujayninfoways-commits/gigalooping.git

# Navigate to the directory
cd gigalooping

# Start local server (Python)
python -m http.server 8000

# Or use Node.js
npm start
```

Then open `http://localhost:8000` in your browser.

## File Structure

```
gigalooping/
├── index.html      # Main HTML file
├── styles.css      # Styling
├── script.js       # Three.js and interactivity
├── package.json    # Project metadata
└── README.md       # This file
```

## Customization

### Change Colors
Edit `:root` variables in `styles.css`:
```css
:root {
    --primary: #0066ff;      /* Primary color */
    --secondary: #00d4ff;    /* Secondary color */
    --dark: #0a0e27;         /* Background */
}
```

### Modify 3D Objects
Edit the `createObjects()` function in `script.js` to add/modify 3D geometries.

### Add Sections
Add new sections in `index.html` and style them in `styles.css`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. Use WebGL renderer for better performance
2. Keep geometry complexity moderate
3. Use requestAnimationFrame for smooth animations
4. Optimize textures and lighting

## Future Enhancements

- [ ] Add particle effects
- [ ] Implement scroll animations
- [ ] Add more interactive 3D models
- [ ] Create portfolio showcase with 3D elements
- [ ] Add sound/music integration
- [ ] Mobile performance optimization

## License

MIT License - Feel free to use this for your projects

## Contact

Visit: https://gigalooping.com/

---

Created with ❤️ for a professional web experience
