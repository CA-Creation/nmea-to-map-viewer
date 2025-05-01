# NMEA to Map Viewer

This is a simple web application that converts NMEA `$GPRMC` code to GPS coordinates and displays the location on an interactive map using **Leaflet.js** and **OpenStreetMap**.

## Features
- Input a valid **NMEA `$GPRMC` sentence**.
- Parse the GPS coordinates (latitude, longitude).
- Show the location on an interactive map.
- Smooth animations and modern UI design.
- Lightweight and responsive layout.

## Technologies Used
- **HTML5**: Structure and content of the page.
- **CSS3**: Styling and animations, with a clean, modern design.
- **JavaScript**: Functionality for processing NMEA code and manipulating the map.
- **Leaflet.js**: Open-source JavaScript library for interactive maps.
- **OpenStreetMap**: Free, open-source map tiles.
- **Google Fonts**: For a modern and clean font style (Outfit).
  
## Installation Instructions

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/CA-Creation/nmea-to-map-viewer.git
  
## How to Use
Open the nmea to map viewer.html file in your browser.
Paste a valid NMEA $GPRMC sentence into the input field (e.g., $GPRMC,092204.999,A,5321.6802,N,00630.3372,W,0.06,31.66,280511,,,A*77).
Click the Show Location button to plot the GPS coordinates on the map.
The map will automatically center on the specified coordinates, and a marker will appear at the GPS location.

## Example NMEA Code
 ```bash
$GPRMC,092204.999,A,5321.6802,N,00630.3372,W,0.06,31.66,280511,,,A*77

