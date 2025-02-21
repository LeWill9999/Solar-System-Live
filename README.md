# Solar System Live

A real-time, interactive visualization of our solar system, including planets, dwarf planets, major asteroids, comets, spacecraft, and natural satellites. The visualization uses NASA's HORIZONS API for accurate celestial body positions and orbital calculations.

## 🌟 Features

### Celestial Bodies
- All planets including Pluto (restored as requested!)
- Major moons of planets:
  - Earth's Moon
  - Mars' Phobos and Deimos
  - Jupiter's Galilean moons (Io, Europa, Ganymede, Callisto)
  - Saturn's major moons (Titan, Rhea, Iapetus)
  - Uranus' largest moons (Titania, Oberon, Miranda)
  - Neptune's Triton

### Asteroid Belt
Major asteroids between Mars and Jupiter:
- Ceres (dwarf planet)
- Vesta
- Pallas
- Hygiea
- Interamnia
- Europa (52)
- Davida
- Sylvia
- Cybele
- Eunomia

### Comets
Notable comets with dynamic tails:
- Halley's Comet
- Hale-Bopp
- Encke
- Tempel 1
- Wild 2
- Churyumov-Gerasimenko
- Swift-Tuttle
- Borrelly
- Giacobini-Zinner
- Hartley 2

### Spacecraft & Artificial Satellites
Real-time tracking of major space missions:
- Deep Space Missions:
  - Voyager 1
  - Voyager 2
  - New Horizons
- Space Telescopes:
  - James Webb Space Telescope (at L2 point)
  - Hubble Space Telescope
- Earth-Orbiting:
  - International Space Station (ISS)
- Solar System Explorers:
  - Parker Solar Probe
  - Juno (Jupiter)
  - MAVEN (Mars)
  - Cassini (Historical Saturn position)

## 🚀 Technical Features
- Real-time position updates using NASA HORIZONS API
- Fallback calculations for when API data is unavailable
- Accurate orbital mechanics and scaling
- Interactive 3D grid system
- Mobile-responsive design
- Distinctive visual styles for different object types:
  - Planets with unique gradients and shadows
  - Asteroids with rocky textures
  - Comets with dynamic glowing tails
  - Spacecraft with metallic appearance
  - Moons with appropriate size scaling

## 🎯 Development Process
This project was developed using an innovative "vibe coding" approach, leveraging several AI tools:

### AI Assistance
- **Cursor AI**: Primary development environment using:
  - Claude 3.5 Sonnet for code generation and problem-solving
  - Composer for complex feature integration
- **Audio-to-Text Tools**:
  - SuperWhisper: Voice command transcription
  - Wispr Flow: Natural language processing for development flow

This approach allowed for a more natural and intuitive development process, combining traditional coding with AI-assisted development and voice-based programming.

## 🌐 Access
Visit [https://LeWill9999.github.io/Solar-System-Live/](https://LeWill9999.github.io/Solar-System-Live/) to view the live visualization.

## 📱 Compatibility
- Works on desktop and mobile browsers
- Touch-friendly controls for mobile devices
- Responsive design adapts to screen size

## 🔄 Updates
The visualization updates every 5 seconds with new position data, ensuring accurate representation of our dynamic solar system.

## 🎨 Visual Design
- Unique color schemes for different object types
- Dynamic lighting and shadow effects
- Intuitive size scaling for visibility
- Clear labeling system with hover effects
- Distinctive orbit styles for different object categories

---

*This project demonstrates the potential of combining traditional astronomical data with modern web technologies and AI-assisted development to create an engaging educational tool.*

## Tracked Objects

### Planets
1. Mercury
2. Venus
3. Earth (with Moon)
4. Mars
5. Jupiter (with Galilean moons)
   - Io
   - Europa
   - Ganymede
   - Callisto
6. Saturn (with Titan)
7. Uranus
8. Neptune
9. Pluto (dwarf planet)

### Major Asteroids (Asteroid Belt)
1. Ceres (dwarf planet)
2. Pallas
3. Juno
4. Vesta
5. Hygiea
6. Euphrosyne
7. Cybele
8. Psyche
9. Europa (asteroid, not to be confused with Jupiter's moon)
10. Eunomia

### Notable Comets
1. Halley's Comet (1P/Halley)
2. Encke (2P/Encke)
3. Tempel 1 (9P/Tempel)
4. Wild 2 (81P/Wild)
5. Churyumov-Gerasimenko (67P)
6. Hale-Bopp (C/1995 O1)
7. Hyakutake (C/1996 B2)
8. McNaught (C/2006 P1)
9. Lovejoy (C/2011 W3)
10. NEOWISE (C/2020 F3)

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
- v2.0.0: Current version with comprehensive celestial object tracking

## 🚀 Upcoming Features

### 3D Visualization Enhancement
- Full 3D rendering of all celestial bodies
- Interactive camera controls for:
  - Free orbit around the solar system
  - Following specific objects
  - Viewing from any object's perspective
- Realistic 3D models for:
  - Spacecraft with accurate geometries
  - Planet surface features
  - Asteroid shapes
  - Comet nucleus details

### Advanced Interaction
- Object selection and focus mode
- Detailed information panels with real-time data
- Time controls for:
  - Historical positions
  - Future predictions
  - Time acceleration/deceleration
- Distance measurements between objects

### Visual Improvements
- Enhanced lighting effects
- Realistic shadow casting
- Improved texture mapping
- Atmospheric effects for planets
- More detailed comet tail physics
- Asteroid belt density visualization

### Educational Features
- Guided tours of the solar system
- Historical space mission paths
- Educational overlays and annotations
- Astronomical event predictions
- Integration with educational resources

### Technical Enhancements
- WebGL implementation for better performance
- Improved mobile controls
- VR/AR support
- Offline mode capabilities
- Enhanced API integration

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Acknowledgments

- NASA JPL for the HORIZONS system
- Minor Planet Center for asteroid data
- JPL Small-Body Database for comet data 