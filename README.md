# Enhanced Earthquake Visualization with Python and Folium

This project aims to redesign global earthquake data visualizations to improve clarity, interactivity, and usability for general users, researchers, and decision-makers. It utilizes real-time data from the United States Geological Survey (USGS) and Python-based tools to display recent seismic activity on an interactive map.

# Acknowledgement
This project has benefitted from the conversations at the Digital Technology for Sustainability Symposium at Duke Kunshan University on April 18. We especially thank Prof. Chandrashekar Radhakrishnan, Prof. David Schaaf and Prof Dongping Liu for his insights that helped improve the work, and the conference Chair members Prof Luyao Zhang, Prof Fan Liang and Prof Charles Chang for making the symposium happen.

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

The output are fully interactive HTML maps:

EarthQuake Visualization Redesign colored with Level Index Ranges:https://static.us.edusercontent.com/files/yGm6TGjSeMRKRRvulUw9ViG0

EarthQuake Visualization Redesign colored with Gradual Level Index:https://static.us.edusercontent.com/files/c3RZfxzo5yOq2CmHov5oaCm3

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

Revised Version with Point Clustering and Text Labels

<img width="1426" alt="Screenshot 2025-04-20 at 22 48 55" src="https://github.com/user-attachments/assets/125d3ac9-9bf5-4a4e-8615-0c6a701c699a" />





## 4. Future Research

The visit to the **Zhouzhuang Mystery of Life Museum** sparked innovative ideas for bridging digital humanities, biodiversity education, and community engagement. Although the museum’s anatomical displays of humans and animals were visually impactful, they also revealed challenges in **accessibility** for lay audiences and those who may find such content distressing.

A promising future direction involves transforming these exhibits into an immersive **Augmented Reality (AR)** experience. Leveraging advanced technologies like **Apple Vision Pro**, users could explore anatomical models interactively—zooming in, navigating at their own pace, and engaging in a more personalized, emotionally considerate manner. By integrating **multilingual support**, the experience would become more inclusive for global visitors.

> This vision emphasizes ethical science communication, sensitivity in design, and user empowerment—aligning with the broader goals of digital humanities while promoting inclusive biological literacy.

**AR-driven storytelling** holds great potential to inspire cross-disciplinary learning through immersive and thoughtful design.
<img width="219" alt="image" src="https://github.com/user-attachments/assets/8c3fe858-392e-485a-9a24-c4c6d5199a6b" />

*Figure 7. The specimen of the red panda in Zhouzhuang Mystery of Life Museum*

---

## Statement of Contribution to Sustainable Development Goals (SDGs)

This project actively contributes to multiple **United Nations Sustainable Development Goals (SDGs)** through its innovative applications in global data visualization.

- By enhancing climate risk assessments via interactive maps and dynamic features, the work supports **SDG 13: Climate Action** by:
  - Empowering policymakers and communities to interpret climate projections
  - Prioritizing infrastructure resilience
  - Mitigating environmental impacts

<div align="center">
  <img src="https://github.com/user-attachments/assets/0a4d7840-866c-40d8-8cf6-fa8fcae0872d" alt="SDG 13 Icon" width="200"/>
</div>

- The development of **TRAFFICVIS**, an interactive tool for detecting human trafficking patterns, contributes to **SDG 16: Peace, Justice, and Strong Institutions** by:
  - Enabling law enforcement and anti-trafficking stakeholders to identify organized criminal activities
  - Protecting vulnerable populations
  - Promoting social justice

<div align="center">
  <img src="https://github.com/user-attachments/assets/5b41e8ec-44dd-43f5-b072-7750fc4f3d82" alt="SDG 16 Icon" width="200"/>
</div>

- The **real-time seismic activity visualization system** advances **SDG 11: Sustainable Cities and Communities** through:
  - Raising public awareness of natural hazards
  - Improving disaster preparedness
  - Informing urban planning to reduce risks in vulnerable regions

<div align="center">
  <img src="https://github.com/user-attachments/assets/f81a62a7-5d94-4307-add7-2c6f7a4060d0" alt="SDG 11 Icon" width="200"/>
</div>


