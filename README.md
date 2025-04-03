# Finnish Train Tracker (Simulation)

A data visualization project that simulates train movements across Finland in real-time with interactive features and analytics.

## Project Overview

This project provides a simulated real-time visualization of train movements across major Finnish cities. It uses interactive maps, dynamic charts, and real-time tracking to create an engaging data visualization experience.

## Features

- **Interactive Map**: Visualizes train movements across Finland using Leaflet.js
- **Real-time Simulation**: Simulates train movements with realistic speed and route calculations
- **Multiple Train Types**: Includes different train types (Long-distance, Commuter, Cargo, Locomotive, Shunting)
- **Data Analytics**: Provides real-time charts and statistics about train speeds and distribution
- **Customizable Settings**: Allows adjustment of simulation parameters (train count, speed, update interval)
- **Responsive Design**: Works well on different screen sizes

## How to Use

1. **Start/Stop Tracking**: Use the glowing buttons to start or stop the train tracking simulation
2. **Settings**: Click the Settings button to adjust simulation parameters:
   - Train Count: Change the number of trains in the simulation
   - Min/Max Speed: Adjust the speed range for trains
   - Update Interval: Control how frequently the simulation updates
3. **Chart Analysis**: Use the dropdown menu in the chart section to switch between different data visualizations:
   - Speed Over Time: View average speeds of different train types
   - Train Count by Type: See the distribution of train types
   - Speed Distribution: Analyze the speed ranges of different train types

## Technical Details

- Built with vanilla JavaScript, HTML5, and CSS3
- Uses Leaflet.js for map visualization
- Uses Chart.js for data visualization
- Integrates with Finnish open data API for realistic train data
- No backend required - runs entirely in the browser
- Simulates realistic train movements using vector calculations

## Installation

No installation required. Simply open the `index.html` file in any modern web browser to run the simulation.

```bash
# If you have Python installed, you can run a simple HTTP server
python -m http.server

# Then open http://localhost:8000 in your browser
```

## Future Enhancements

- Enhanced real-time data synchronization with Finnish train data API
- Additional analytics and visualization options
- User accounts to save preferred settings
- Mobile app version with notifications
- Historical data analysis and trend visualization

## Project Creator

**Fowsi Mohamoud Dayib**  
Data Engineering Project  
[LinkedIn Profile](https://www.linkedin.com/in/fowsi-mohamoud-dayib-832094274/)

## License

This project is available for educational and personal use.

---

© 2025 Fowsi Mohamoud Dayib
