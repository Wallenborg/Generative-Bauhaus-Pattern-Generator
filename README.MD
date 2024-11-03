# Generative Bauhaus Pattern Generator

## Overview
This project is a **Generative Bauhaus Pattern Generator** that dynamically creates unique patterns inspired by the design principles of the Bauhaus movement. The application generates various shapes, arranged algorithmically to produce compositions that are both precise and unpredictable. Each pattern refreshes every 4 seconds, creating a continuously evolving visual experience.

## Features
- **Bauhaus-Inspired Patterns**: The generator uses a set of Bauhaus colors and shapes (circles, lines, grids, squares) to create each pattern.
- **Dynamic Shape Placement**: Shapes are randomly positioned on the screen with rotation and color variations to enhance unpredictability.
- **Automated Pattern Refresh**: Every 4 seconds, a new pattern is generated, clearing the old one to start afresh.
- **Responsive Hero Section**: A hero section with a 'START' button launches the pattern generation process and disappears to reveal the main canvas.

## Technologies
- **HTML, CSS, JavaScript**: Basic technologies for structuring and styling the webpage, along with JavaScript for logic and interactivity.
- **Bauhaus Color Palette**: A carefully selected color scheme that aligns with Bauhaus aesthetics.

## Getting Started

1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/your-username/generative-bauhaus-pattern.git
    cd generative-bauhaus-pattern
    ```

2. **Open the HTML file**: 
   Open `index.html` directly in your browser.

3. **Usage**: 
   - On page load, the hero section appears with the project title and description.
   - Click **START** to initiate the pattern generation. This hides the hero section and begins the 4-second interval pattern refresh.

## How It Works
- **Shape Generation**: Shapes are created in various types (outlined circle, filled circle, line, grid, square) with randomized sizes, colors, and positions.
- **Pattern Refreshing**: Shapes are removed and regenerated every 4 seconds to ensure a constantly changing visual.
- **Randomization**: Position, rotation, and size of shapes are randomized, resulting in a unique configuration for each refresh cycle.

## Customization
To adjust the number of shapes, pattern update interval, or add new colors to the palette:
- Modify the `totalShapes` variable within the `placementShape()` function.
- Change `bauhausColors` in the script to add new colors or remove existing ones.
- Adjust the interval time in `setInterval(placementShape, 4000);` for faster or slower pattern refreshes.

## License
This project is open-source under the [MIT License](LICENSE).

## Acknowledgments
Inspired by Bauhaus design principles, this project leverages simplicity, color, and geometry to create a digital homage to the influential art movement.

Enjoy experimenting with generative design!
