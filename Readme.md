# Button Ripple Effect

This project implements a **button ripple effect** using HTML, CSS, and JavaScript. The effect enhances user interaction by creating an expanding ripple when the button is hovered over. This simple yet engaging animation can be easily integrated into any web project.

## Features
- **Interactive Animation**: The ripple originates from the point where the mouse hovers, giving immediate feedback.
- **Customizable Design**: The ripple’s color, size, and animation duration can be easily customized via CSS variables.
- **Lightweight and Responsive**: The code is efficient and works smoothly across various screen sizes without impacting performance.

## Project Structure
```
├── index.html
├── style.css
└── script.js
```

## How It Works
The ripple effect is created by:
- Detecting the mouse hover position using JavaScript.
- Setting the coordinates as CSS variables to create a ripple effect from the exact point.
- Expanding a circular `::before` element using CSS animations.

## Installation and Usage
1. Clone or download the repository:
   ```bash
   git clone https://github.com/username/Button-Ripple-Effect.git
   ```
2. Open the `index.html` file in your browser to see the effect in action.

## Customization
You can easily customize the ripple effect:
- **Ripple Color**: Modify the color in the `btn::before` CSS selector.
- **Animation Duration**: Adjust the `transition` property in the CSS for faster or slower animation.
- **Ripple Size**: Change the `width` and `height` in the `btn:hover::before` section to control the final size of the ripple.

## Conclusion
This button ripple effect adds an interactive and visual element to any web project. It’s simple to implement and customize, making it a great addition to modern web designs.

