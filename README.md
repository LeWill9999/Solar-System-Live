# Solar System Live Visualization

A real-time, interactive visualization of our solar system, including planets, major asteroids, and comets. The visualization uses NASA's HORIZONS API for accurate celestial body positions and orbital calculations.

## Features

- **Real-time Planetary Positions**: Uses NASA HORIZONS API for accurate positioning
- **Complete Solar System**: 
  - All 8 planets + Pluto
  - Major moons (Earth's Moon, Jupiter's Galilean moons, Saturn's Titan)
  - 10 significant asteroids (Ceres, Pallas, Juno, Vesta, etc.)
  - 10 notable comets (Halley's, Hale-Bopp, NEOWISE, etc.)
- **Accurate Orbital Mechanics**:
  - Proper orbital periods
  - Correct orbital inclinations
  - Realistic object scaling
- **Visual Features**:
  - Realistic planet textures and colors
  - Comet tails pointing away from Sun
  - Visible orbital paths
  - Planet/object labels
  - Saturn's rings
- **Interactive Elements**:
  - Hover effects for celestial bodies
  - Real-time date and time display

## Technologies Used

- HTML5
- CSS3 (with 3D transforms)
- JavaScript (Vanilla)
- NASA HORIZONS API

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/LeWill9999/Solar-System-Live.git
   ```

2. Open `solar_system_live.html` in a modern web browser
   - Recommended browsers: Chrome, Firefox, Safari
   - Requires WebGL and 3D CSS transform support

3. The visualization will automatically start with:
   - Current date/time display
   - Real-time planetary positions
   - Animated orbital motion

## Data Sources

- Planetary positions: NASA HORIZONS Web-Interface
- Orbital periods: NASA Planetary Data System
- Asteroid data: Minor Planet Center
- Comet data: JPL Small-Body Database

## Project Structure

```
Solar-System-Live/
├── solar_system_live.html    # Main application file
├── README.md                 # This file
└── versions/                 # Version history
    ├── v4_working_positions/ # Last stable version
    └── v5_current/          # Current version
```

## Version History

- v1.0.0: Initial release with basic solar system visualization
- Future versions will include:
  - Enhanced zoom functionality
  - Detailed information panels
  - Time controls for historical/future positions
  - Additional celestial objects

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Acknowledgments

- NASA JPL for the HORIZONS system
- Minor Planet Center for asteroid data
- JPL Small-Body Database for comet data 