# Enhanced Earthquake Visualization with Python and Folium

This project aims to redesign global earthquake data visualizations to improve clarity, interactivity, and usability for general users, researchers, and decision-makers. It utilizes real-time data from the United States Geological Survey (USGS) and Python-based tools to display recent seismic activity on an interactive map.

## Project Objective

To create a more accessible and visually effective interface for analyzing and understanding recent earthquake events worldwide. The design focuses on:

- Visual clarity (e.g., color-coded magnitude levels)
- Real-time data access
- Interactive exploration
- Public awareness of seismic risk

---

## Features

- **Live Earthquake Feed**: Uses real-time data from USGS GeoJSON API
- **Interactive Map**: Built with Folium, displays earthquake location, time, and magnitude
- **Dynamic Markers**: Circle size and color correspond to magnitude
- **Custom Legend**: Clear scale for quick understanding of severity levels
- **Popup Info Windows**: View event metadata by clicking on map markers
- **Global Scope**: Displays all recorded earthquakes from the past 30 days

---

## Tools & Libraries Used

- **Python**: Core programming language  
- **Requests**: To fetch live GeoJSON data  
- **Pandas**: For data cleaning and transformation  
- **Folium**: For generating Leaflet.js maps  
- **Jupyter Notebook**: Development and testing environment

---

## Data Source

Data is provided by the **United States Geological Survey (USGS)**:
> https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php

Dataset includes:
- Location
- Time (converted from Unix timestamp)
- Magnitude
- Coordinates (latitude & longitude)
- Depth (optional)

---

## Output

The output is fully interactive HTML maps:

### 🖼️ Example Screenshots
- Marker distribution by magnitude
- Color-coded severity (Green < 3.0, Orange: 3.0–4.9, Red ≥ 5.0)
- Zoom and hover-enabled data tooltips

EarthQuake Visualization Redesign colored with Level Index Ranges

<img width="468" alt="image" src="https://github.com/user-attachments/assets/fde78a1b-cd2e-4a2b-bb3e-654e564547e0" />

EarthQuake Visualization Redesign colored with Gradual Level Index

<img width="468" alt="image" src="https://github.com/user-attachments/assets/32ef4ca9-ed3a-4e8f-ae08-e9813de2e529" />

EarthQuake Visualization Details Example when touching the Signal

<img width="450" alt="image" src="https://github.com/user-attachments/assets/2f608471-e080-4fe1-96d0-d3465c603c2c" />


## Citation

United States Geological Survey. “Real-time Earthquake Map.” Last modified April 2025. https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php.

