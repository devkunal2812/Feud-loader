# CURET Loading Screen

A futuristic, cyberpunk-themed loading screen for CURET event at PRKARSH 2026, presented by PRAXIS.

## Features

- 🎨 **Cyberpunk Aesthetic** - Neon blue and pink color scheme with glowing effects
- ✨ **Smooth Animations** - Zoom effects, glitch transitions, and particle system
- 📱 **Fully Responsive** - Optimized for mobile, tablet, and desktop devices
- ⚡ **Performance Optimized** - Adaptive particle count based on screen size
- 🎯 **Interactive Elements** - Custom cursor, hover effects, and dynamic loading bar
- 🌟 **Visual Effects** - Scanlines, vignette, bottom glow, and floating animations

## Technologies Used

- Pure HTML5
- CSS3 (Animations, Gradients, Filters)
- Vanilla JavaScript (Canvas API, Promises, Async/Await)
- Google Fonts (Orbitron, Rajdhani, Bebas Neue)

## Preview

The loading screen features:
1. **Phase 1**: PRKARSH 2026 title reveal with zoom effect
2. **Phase 2**: PRAXIS presents with glitch animation
3. **Phase 3**: Lightning crack transition
4. **Phase 4**: CURET logo with pulsing glow and progress bar
5. **Final**: Homepage with floating logo animation

## Responsive Design

- **Mobile** (≤480px): Optimized text sizes, reduced particle count, hidden custom cursor
- **Tablet** (481px-768px): Medium adjustments for comfortable viewing
- **Desktop** (769px+): Full experience with all effects

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/curet-loading.git
```

2. Open `curet-loading.html` in your browser

That's it! No build process or dependencies required.

## Customization

### Colors
Edit the CSS variables in `:root`:
```css
--blue:       #3366ff;
--blue-bright:#4d7fff;
--pink:       #ff1493;
--pink-hot:   #ff69b4;
--white:      #f8f0ff;
--silver:     #c8aad8;
--bg:         #000000;
```

### Particle Count
Adjust in the `getParticleCount()` function:
```javascript
function getParticleCount() {
  const width = window.innerWidth;
  if (width < 768) return 180;    // Mobile
  if (width < 1440) return 280;   // Tablet/Laptop
  return 380;                      // Desktop
}
```

### Animation Timing
Modify delays in the `run()` function to adjust sequence timing.

## Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## Performance

- Adaptive particle system reduces load on mobile devices
- Hardware-accelerated CSS animations
- Efficient canvas rendering with requestAnimationFrame
- Optimized font loading with display=swap

## License

MIT License - Feel free to use this for your projects!

## Credits

Created for CURET event at PRKARSH 2026
Presented by PRAXIS

---

**Where Rivalries Rise.** ⚡
