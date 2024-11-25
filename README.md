# Cybertruck Nighttime Road Trip

This project is an animated SVG-based visual scene featuring a Tesla Cybertruck traveling through a nighttime road trip. The scene incorporates moving mountains, trees, a road, and other landscape elements with various animations and gradients to create an immersive experience.

## Features

- **Animated Landscape:** Moving mountains, trees, and roadside elements for a dynamic visual effect.
- **Gradients:** Various linear gradients to add depth and realism to the scene.
- **Cybertruck Animation:** A Cybertruck traveling on a road with realistic features such as tires, lights, and shadows.
- **SVG Filters:** Gaussian blur filters for creating depth and enhancing visuals.
- **Light Effects:** Headlight with a glowing effect that illuminates part of the road.

## Technologies Used

- **HTML5**: The structure of the webpage.
- **SVG (Scalable Vector Graphics)**: For creating and animating the scene.
- **CSS**: External stylesheet for styling (referenced as `style.css`).
- **JavaScript**: For enhanced animations (if included in `style.css` or external files).

## Setup

1. Clone the repository or download the files.
2. Ensure the following files are present:
   - `index.html`: The main HTML file containing the SVG code.
   - `style.css`: External CSS file for additional styling (if implemented).
3. Open the `index.html` file in a web browser to view the animation.

## How It Works

- **SVG Elements**: The scene is composed of SVG elements such as `<rect>`, `<circle>`, `<path>`, and `<defs>` for gradients and filters.
- **Animation**: 
  - The `<animateTransform>` element is used to create movement for mountains, trees, and other components.
  - Gaussian blur filters (`<filter>`) are applied for depth effects.
- **Gradients**: Custom linear gradients are defined in `<defs>` to simulate different parts of the scene like the sky, grass, and car windows.

## Customization

- Modify colors in the gradient definitions inside the `<defs>` section.
- Adjust animation speeds by changing the `dur` attribute values in `<animateTransform>` elements.
- Add or remove SVG elements to change the complexity of the scene.
