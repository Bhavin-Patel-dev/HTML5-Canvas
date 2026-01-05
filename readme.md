## 🎯 Overview

This project is an interactive drawing canvas that creates beautiful rainbow-colored strokes with dynamically changing brush width. As you draw, the stroke color cycles through the entire HSL color spectrum (0-360 degrees), creating a mesmerizing rainbow effect. The brush width also animates between 1 and 100 pixels, adding another dimension of visual interest to your artwork.

Built entirely with vanilla JavaScript and the HTML5 Canvas API, this project demonstrates core web development concepts without any external dependencies or frameworks.

## ✨ Features

### 🌈 Core Functionality

- **Rainbow Color Cycling**: Automatic HSL color progression through the full spectrum

- **Dynamic Brush Width**: Animated line width that oscillates between 1px and 100px

- **Smooth Drawing**: Round line caps and joins for natural-looking strokes

- **Responsive Canvas**: Automatically resizes to fit any screen size

- **Real-time Drawing**: Immediate visual feedback as you draw

### 🎮 User Experience

- **Mouse-based Drawing**: Click and drag to create artwork

- **Natural Controls**: Drawing only occurs when mouse button is held down

- **Boundary Detection**: Automatically stops drawing when mouse leaves canvas

- **Full-screen Canvas**: Utilizes entire browser viewport

### ⚡ Performance

- **Lightweight**: Zero dependencies, pure vanilla JavaScript

- **Efficient Rendering**: Optimized canvas operations

- **Minimal File Size**: Only 2 files (HTML + JS)

### Try It Out:

1. Click and hold your mouse on the canvas

2. Move your mouse to draw colorful strokes

3. Watch as colors transition through the rainbow spectrum

4. Notice the brush width changing as you draw

## 🛠 Technologies Used

- **HTML5**: Canvas element for drawing surface
- **JavaScript (ES6+)**: Core application logic
- **Canvas 2D API**: All drawing operations

### Key Canvas APIs Implemented

```javascript
// Canvas Context Methods
ctx.getContext("2d"); // Get 2D rendering context
ctx.beginPath(); // Start new path
ctx.moveTo(x, y); // Move pen to position
ctx.lineTo(x, y); // Draw line to position
ctx.stroke(); // Render the path

// Canvas Properties
ctx.strokeStyle; // Color of strokes
ctx.lineWidth; // Width of lines
ctx.lineCap = "round"; // Rounded line ends
ctx.lineJoin = "round"; // Rounded line corners
```

## 📦 Getting Started

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Bhavin-Patel-dev/HTML5-Canvas.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd HTML5-Canvas
   ```

### Running the Project

**Option 1: Direct Opening**
Simply double-click `index.html` to open in your default browser.

**Option 2: VS Code Live Server**

1. Install Live Server extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

**Option 3: Python HTTP Server**

```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

**Option 4: Node.js http-server**

```bash
npx http-server
```

## 📁 Project Structure

```
HTML5-Canvas/
│
├── index.html          # HTML structure with canvas element
├── script.js           # All drawing logic and event handlers
└── README.md           # Project documentation
```

## 🎓 Key Learning Takeaways

### 1. **HTML5 Canvas Fundamentals**

- Setting up and accessing canvas context

- Understanding the coordinate system

- Drawing paths with `beginPath()`, `moveTo()`, and `lineTo()`

- Applying strokes with `stroke()`

### 2. **Mouse Event Handling**

- `mousedown` - Initiating drawing mode

- `mousemove` - Continuous drawing while mouse moves

- `mouseup` - Stopping drawing when button released

- `mouseout` - Preventing drawing outside canvas bounds

- Using `offsetX` and `offsetY` for accurate coordinates

### 3. **Color Theory and HSL**

- HSL color model (Hue, Saturation, Lightness)

- Creating color transitions programmatically

- Understanding color spaces vs RGB

- Hue cycling for rainbow effects (0-360 degrees)

### 6. **JavaScript Best Practices**

- ES6 destructuring assignment for cleaner code

- Arrow functions for concise event handlers

- Boolean flags for state management

- Early returns for cleaner conditional logic

### 7. **Canvas Styling Properties**

- `lineCap: 'round'` - Smooth line endings

- `lineJoin: 'round'` - Smooth corner connections

- `strokeStyle` - Dynamic color assignment

- `lineWidth` - Programmatic width control

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

### Development Guidelines

- Maintain vanilla JavaScript (no frameworks)
- Keep code simple and readable
- Test in multiple browsers
- Update README for new features
