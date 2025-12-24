# CityGraph
This project is an interactive city graph visualizer built with Leaflet, where users can place nodes on a map, generate real road-based routes between them, compute the shortest route, and explore the network using DFS.

# City Graph

## Project Description
City Graph is a web-based project that shows how graph concepts work using a city map. Users can place nodes on a map, connect them using roads, and visualize different graph operations like finding the shortest path or exploring all connections.

## Tools and Technologies
- **HTML** – Structure of the webpage  
- **CSS** – Styling and layout  
- **JavaScript** – Logic and graph implementation  
- **Leaflet.js** – Interactive map  
- **OpenStreetMap** – Map data  
- **OSRM API** – Road routing between locations  

## Graph Representation
- Each location placed on the map is treated as a **node**.
- Roads between nodes act as **edges**.
- Distance between nodes is used as the **weight**.
- The graph is stored using an **adjacency list**.

## Features
- Add nodes by clicking on the map  
- Show possible routes between selected nodes  
- Find the shortest route between two nodes  
- Explore the graph using Depth First Search (DFS)  
- Clear the map and reset the graph  

## How the Program Works
1. The map is displayed using Leaflet.
2. When the user clicks on the map, a node is created.
3. Routes between nodes are fetched using real road data.
4. The distances are stored in a graph structure.
5. Graph algorithms run on this data and the results are shown on the map.

## Purpose of the Project
The purpose of this project is to understand how graph data structures and algorithms can be applied to real-world problems using maps and routing data.
