# 🌍 Project Title: [Reusing Decommissioned Aircrafts to Jump Start Launch Capabilities to Low Earth Orbit]
**Team:** Youth Orbit 
**Event:** NASA Space Apps Challenge 2025  
**Challenge:** Commercializing Low Earth Orbit

A demo for Nasa Space Apps which includes a simulation of an air-launch platform traversing to their altitude and drop a rocket to deliver a payload to Low Earth Orbit.

## 🛰️ Overview
Youth Orbit presents a concept to commercialize Low Earth Orbit (LEO) using repurposed aircraft as air-launch platforms.
This demo showcases a flight and launch simulation, visualized on an interactive 3D globe powered by Cesium Ion, to demonstrate how an aircraft-based system can efficiently deliver small payloads into orbit.

The simulation models the aircraft’s takeoff, flight path, launch release, and return trajectory, providing an intuitive visualization of how such a scalable and sustainable LEO access method could work.

## ✈️ Features
- Realistic 3D visualization of an aircraft performing an air launch.
- Simulated flight trajectory including ascent, payload release, and return.
- Designed for scalability and feasibility studies in future commercial LEO operations.
- Runs directly in the browser — no installation required.

## ⚙️ Technical Details
- Frontend: HTML, CSS, JavaScript
- 3D Visualization: CesiumJS
- Data: Static flight trajectory data (JSON) generated via Python
- Deployment: GitHub Pages (linked to a GoDaddy domain)

The Python script generates position and altitude data points that define the aircraft’s route. These are then visualized using CesiumJS to illustrate the launch trajectory in near-real-time simulation.

## Contributors
- Jonathan Suara Patty

### 3D Resources and Data

- **Sketchfab 3D Models**  
  Used for the rocket object in the demo.  
  - Source: [Sketchfab](https://sketchfab.com/3d-models/rocket-7ac80b6d4701415a85e492ec24185a21)  
  - License: Varies per model – all models used comply with the creator’s license.  

- **NASA Datasets**  
  Used for the plane object in the demo.  
  - Source: [NASA 3D Resources](https://airbornescience.nasa.gov/content/3D_Models_Gallery)  
  - License: Public Domain / Open Government License  

  Used for the payload object in the demo.  
  - Source: [NASA 3D Models Gallery](https://science.nasa.gov/3d-resources/cubesat-1-ru-generic)  
  - License: Public Domain / Open Government License  