# Solar System Simulation

A 3D interactive solar system simulation built with A-Frame, a web framework for building virtual reality experiences.

## Overview

This project creates an interactive 3D model of our solar system, including:

- The Sun with realistic textures and lighting
- All eight planets (Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune)
- Earth's moon
- Saturn's rings
- Orbital paths for each planet
- Rotating animations that simulate planetary movement

The simulation allows users to navigate through the solar system using mouse and keyboard controls, providing an immersive educational experience about the relative positions, sizes, and movements of planets in our solar system.

## Demo

[View Live Demo](https://fcm4102009923.netlify.app/)

## Features

- Realistic planet textures using high-quality image maps
- Accurate relative sizing of planets
- Animated orbital paths with different speeds to represent orbital periods
- Planetary rotation on axes
- Saturn's distinctive ring system
- Interactive camera controls to explore the simulation
- Responsive design that works across devices
- Beautiful starfield background representing the Milky Way

## Technologies Used

- [A-Frame](https://aframe.io/) - WebVR framework for creating 3D/VR experiences
- HTML5
- JavaScript
- High-resolution planetary textures

## Getting Started

### Prerequisites

- Modern web browser with WebGL support (Chrome, Firefox, Safari, Edge)
- Internet connection (to load the A-Frame library from CDN)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/dogahwisdom/solar-system.git
   ```

2. Navigate to the project directory:
   ```
   cd solar-system
   ```

3. Set up the texture files:
   - Create a `texture` directory
   - Add the required texture files:
     - 2k_stars_milky_way.jpg
     - 2k_sun.jpg
     - 2k_mercury.jpg
     - 2k_venus_atmosphere.jpg
     - 2k_earth_daymap.jpg
     - 2k_mars.jpg
     - 2k_jupiter.jpg
     - 2k_saturn.jpg
     - 2k_uranus.jpg
     - 2k_neptune.jpg
     - 2k_moon.jpg
     - 2k_saturn_ring_alpha.png

4. Open `index.html` in a web browser to view the simulation.

### Texture Resources

You can find high-quality planetary textures from:
- [NASA Visible Earth](https://visibleearth.nasa.gov/)
- [Solar System Scope](https://www.solarsystemscope.com/textures/)
- [James Hastings-Trew's Planets](http://planetpixelemporium.com/planets.html)

## Usage

- **Navigation**: Use WASD keys to move and mouse to look around
- **View Planets Up Close**: Click and drag to rotate the view
- **Zoom**: Use mousewheel to zoom in and out
- **Mobile**: Touch and drag to look around

## Customization

You can customize the simulation by:

1. Modifying planet sizes by changing the radius values
2. Adjusting orbital speeds by changing the animation duration values
3. Replacing textures with your own planetary images
4. Adding additional celestial bodies like comets or asteroids

## Future Enhancements

- Add informational panels with planet facts
- Include asteroid belt and Kuiper belt
- Add more moons for other planets
- Implement day/night cycle for Earth
- Add more detailed ring systems for gas giants
- Include planet tilt angles

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Planetary textures sourced from [Solar System Scope](https://www.solarsystemscope.com/textures/)
- Inspired by NASA's solar system visualizations
- Thanks to the A-Frame community for the amazing framework
