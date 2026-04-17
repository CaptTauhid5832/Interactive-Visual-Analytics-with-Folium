# Interactive-Visual-Analytics-with-Folium
Interactive Visual Analytics with Folium
Here is a professional README content for your Folium notebook. You can use this for your GitHub repository description or a README.md file.

Interactive Visual Analytics with Folium
Project Overview
This project uses Folium to perform interactive geographical analysis of SpaceX launch sites. The goal is to visualize launch patterns, analyze the success/failure distribution at various sites, and examine the proximity of these sites to geographical features like coastlines, highways, and railways.

Key Objectives
Launch Site Location: Mark all major SpaceX launch sites on a world map.

Success vs. Failure Visualization: Use color-coded markers (Green for Success, Red for Failure) to identify performance trends at each site.

Proximity Analysis: Calculate distances between launch sites and nearby infrastructure to understand logistical and safety requirements.

Map Objects & Features
Marker Clusters: Implemented MarkerCluster to manage multiple launch points efficiently, grouping successes and failures by site.

Circle Markers: Added to highlight the specific coordinates of launch pads with a defined radius.

MousePosition: Added a plugin to show real-time Latitude and Longitude for precise distance calculations.

PolyLines: Drew lines between launch sites and nearby points of interest (coasts, railways) using coordinates to visualize proximity.

Technologies Used
Python

Folium (Map rendering)

Pandas (Data manipulation)

Math (Haversine Formula): To calculate distances between two points on the Earth's surface.

Results Summary
Coastline Proximity: All launch sites are located very close to the coastline to ensure spent stages fall into the ocean.

Infrastructure: Sites are strategically placed near highways and railways for easy transport of heavy rocket boosters.

Safety: Most sites maintain a safe distance from major cities to minimize risk in case of mission failure.

How to Use
Open the Interactive_Visual_Analytics_with_Folium.ipynb notebook.

Ensure you have the folium and pandas libraries installed.

Run the cells to generate the interactive maps directly in your browser or Jupyter environment.
