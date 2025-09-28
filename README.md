#India Ocean Hazard Monitoring System
This project is a single-page web application designed to consolidate and visualize real-time hazard data for the Indian Ocean region from various official Indian government sources. It utilizes the Leaflet.js library for map display and relies heavily on CORS proxies to fetch data from live APIs and feeds.

.............................................................................

#Features
Map Visualization: Displays hazard areas using Leaflet.js over dynamic map tiles (OpenStreetMap and Satellite).

Dual-Pane Layout: A responsive interface with a map pane (60%) and a data/control sidebar (40%).

Integrated Feeds: Attempts to fetch and display data from three key government sources:

NDMA CAP Alerts: Common Alerting Protocol (CAP) for general hazards.

IMD Coastal Bulletins: Indian Meteorological Department's weather advisories.

INCOIS Tsunami Warnings: Indian National Centre for Ocean Information Services Tsunami Early Warning System (TEWS).

CORS Fallback: Implements a robust fetch function that tries a direct API call first, then falls back to multiple CORS proxy services (e.g., allorigins.win, corsproxy.io) to circumvent cross-origin restrictions common with government APIs.

Demo Mode: Includes a Demo Hazard Alert button to display a sample cyclone or tsunami alert on the map and sidebar for testing the rendering capability.

Dark & Minimalistic UI: Uses a modern, dark theme for reduced eye strain and a clean aesthetic.
