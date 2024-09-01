# Solar System Visualization

This project is an interactive web-based visualization of the solar system, allowing users to explore planetary motions in both 2D and 3D views.

## Features

- **2D/3D Toggle**: Switch between 2D and 3D representations of the solar system.
- **Adjustable Speed**: Control the speed of planetary motion using a slider.
- **Time Control**: Pause, resume, and reset the simulation.
- **Realistic Orbits**: Planets move in elliptical orbits with accurate relative speeds.
- **Planet Information**: Displays current position of each planet in Astronomical Units (AU).
- **Year Counter**: Shows the number of Earth years elapsed in the simulation.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- HTML5 Canvas for rendering

## Setup

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser.

No additional setup or dependencies are required as this is a pure HTML/CSS/JavaScript project.

## Usage

- **Toggle 2D/3D**: Click the "Toggle 2D/3D" button to switch between view modes.
- **Adjust Speed**: Use the slider to change the simulation speed. The middle position represents 1 Earth year per second.
- **Pause/Resume**: Click the "Pause" button to stop the animation, and "Resume" to continue.
- **Reset**: Click "Reset Time" to start the simulation from the beginning.
- **Zoom**: In 3D mode, planets appear larger or smaller based on their distance from the viewer.

## Planet Representation

- The sun is at the center of the system.
- Planets are shown in order: Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, and Neptune.
- Planet sizes and orbit distances are not to scale but are relatively proportioned for better visualization.

## Customization

You can easily customize this visualization by modifying the `planets` array in the JavaScript code. Each planet object contains properties for name, color, orbital radius (`a`), orbital period, and size.

## Contributing

Contributions to improve the visualization or add new features are welcome. Please feel free to submit pull requests or open issues for any bugs or suggestions.

## License

This project is open-source and available under the MIT License.

## Acknowledgments

This project was created as an educational tool to help visualize planetary motions in our solar system. It's designed to be both informative and visually engaging.

Enjoy exploring the solar system!
