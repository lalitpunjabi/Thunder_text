# Thunder Text Effect

A dynamic canvas-based animation that generates electrifying thunder effects and particle sparks around custom text input. This project uses HTML5 Canvas and JavaScript to create animated lightning bolts, glowing particles, and text rendering that reacts to user interactions.

## Features

- **Thunderbolt Animation:** Randomly generated lightning bolts with glowing effects.
- **Particle Effects:** Sparks and particles that accompany thunderbolts.
- **Dynamic Text Rendering:** Users can input text, which gets animated with thunder and particles.
- **Interactive Canvas:** Clicking on the canvas generates thunder and particle effects at the click position.
- **Customizable Options:** Easily change colors, sizes, lifespans, and other parameters.

## Demo

![Thunder Text Effect Demo](demo.gif)

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- Basic understanding of HTML and JavaScript (optional)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/thunder-text-effect.git
   cd thunder-text-effect
   ```

2. **Open the project:**
   Simply open `index.html` in your preferred browser.

### Usage

1. Open `index.html` in your browser.
2. Type text into the input field to see the thunder animation on your custom text.
3. Click anywhere on the canvas to generate random thunder and particle effects.

## Code Structure

- **Thunder:** Generates the main lightning bolt effect.
- **Spark:** Handles individual spark particles.
- **Particles:** A collection of sparks emitted during thunder strikes.
- **Text:** Renders and animates user-inputted text with thunder effects.
- **Main Loop:** Updates and renders the animation continuously.

## Customization

You can customize various aspects of the animation directly in the JavaScript code:

- **Thunder Color & Glow:** Modify `color` and `glow` properties in the `Thunder` function.
- **Particle Behavior:** Adjust lifespan, friction, and velocity in the `Spark` and `Particles` functions.
- **Text Style:** Change font, size, and color in the `Text` function.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- HTML5 Canvas for powerful 2D rendering.
- Inspiration from dynamic particle and thunder animations.

Enjoy the electrifying effect! ⚡

