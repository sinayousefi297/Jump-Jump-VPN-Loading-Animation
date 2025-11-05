
# Jump Jump VPN Loading Animation

A beautiful, responsive loading animation featuring rotating rings and animated dots for Jump Jump VPN application.


## ✨ Features

- **6 Animated Rings**: Multiple rotating rings with varying speeds and directions
- **Quarter Rings**: Additional visual elements for depth and complexity
- **Animated Dots**: Pulsing dots that follow ring rotation
- **Fully Responsive**: Adapts to all screen sizes using modern CSS units
- **Smooth Performance**: Optimized animations using requestAnimationFrame
- **Customizable**: Easy to modify colors, sizes, and animation speeds

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/jump-jump-vpn-loading.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd jump-jump-vpn-loading
   ```

3. **Open in browser**
   ```bash
   open index.html
   ```

   Or simply double-click the `index.html` file.

## 🛠️ Customization

### Changing the Logo
Replace `profile.jpg` with your own logo image in the project root directory.

### Modifying Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: rgba(0, 168, 255, 0.3);
    --secondary-color: rgba(0, 210, 255, 0.5);
    --accent-color: rgba(0, 255, 242, 0.7);
}
```

### Adjusting Animation Speeds
Modify animation durations in the CSS:
```css
.ring-1 {
    animation-duration: 8s; /* Change this value */
}
```

## 📁 File Structure

- `index.html` - Main HTML structure
- `style.css` - All styles and animations
- `profile.jpg` - Logo image (replace with your own)
- Embedded JavaScript - Handles dot animation synchronization

## 🎨 CSS Architecture

The project uses a modular CSS approach:

- **Base Styles**: Reset and container layout
- **Ring System**: 6 main rings with quarter ring variants
- **Dot Animation**: Pulsing dots with coordinated movement
- **Responsive Design**: Viewport-based units for scalability
- **Animation Keyframes**: Smooth rotation and pulse effects

## ⚙️ Technical Details

### Technologies Used
- HTML5
- CSS3 (Animations, Transforms, Variables)
- Vanilla JavaScript (ES6+)

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Performance Features
- Hardware-accelerated transforms
- Efficient requestAnimationFrame usage
- Minimal DOM manipulations
- Optimized CSS animations

## 🔧 Development

### Adding More Rings
1. Add HTML element: `<div class="ring ring-7"></div>`
2. Define CSS styles for the new ring
3. Update JavaScript if adding connected dots

### Custom Dot Patterns
Modify the dot configuration in JavaScript:
```javascript
dots: [
    { element: document.querySelector('.dot-1a'), angle: 0 },
    { element: document.querySelector('.dot-1b'), angle: 120 },
    { element: document.querySelector('.dot-1c'), angle: 240 }
]
```

## 🎯 Use Cases

- VPN application loading screen
- Website preloader
- App loading indicator
- Presentation background animation
- Dashboard loading state
