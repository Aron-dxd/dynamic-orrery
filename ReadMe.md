# Create an Orrery Web App that Displays Near-Earth Objects

This project is a submission for the web app created as part of the NASA Space Apps Challenge. An orrery can depict various types of celestial bodies, including planets, **Near-Earth Comets (NEC)**, **Near-Earth Asteroids (NEA)**, and a subset of NEAs called **Potentially Hazardous Asteroids (PHA)**. Collectively, NEC, NEA, and PHA are known as **Near-Earth Objects (NEO)**. 

This project aims to depict an interactive **dynamic orrery**, where the positions of celestial bodies such as planets, NECs, NEAs, and PHAs change over time to accurately reflect their orbital motion around the Sun.

**Keplerian parameters**, named after Johannes Kepler (1571-1630), describe an elliptical orbit; these parameters include:
- **Eccentricity (e)**: Describes how elongated an orbit is.
- **Semi-major axis (a)**: Defines the size of the orbit.
- **Inclination (i)**: The tilt of the orbit relative to the reference plane.
- **Argument of periapsis (w)**: The orientation of the elliptical orbit.
- **True anomaly (v)**: The position of the celestial body along the orbit.
- **Longitude of the ascending node (om)**: The horizontal orientation of the orbit.

## Features

- **Interactive 3D Environment**: Navigate through a realistic 3D simulation of our Solar System with zoom and rotation controls for exploring different perspectives.
- **Planetary Motion**: Planets and other celestial bodies move in their actual orbits around the Sun using **Keplerian parameters** for realistic orbital paths.
- **Realistic Textures**: High-quality textures are used for each planet, ensuring visual accuracy.
- **Intuitive Controls**: Users can easily explore the Solar System using controls from OrbitControls (Three.js).
- **Data-Driven Simulation**: Orbital data is fetched from a JSON file (`planets.json`), containing essential Keplerian elements for accurate real-time calculations of planetary positions.

## Technologies Used

- **Three.js**: JavaScript library for rendering planets, the Sun, and the environment in 3D.
- **HTML5 and CSS3**: For webpage structure and styling.
- **JavaScript (ES Modules)**: For creating and managing the 3D scene, importing required Three.js modules, and handling user interactions.
- **Dat.GUI**: Provides a graphical user interface for controlling certain parameters of the 3D scene.

