# Campus Pedestrian Flow & Bottleneck Visualizer

An interactive 2D agent-based simulation for exploring pedestrian movement, congestion, bottlenecks, travel time, and throughput across a synthetic university campus.

## Overview

This project simulates pedestrians moving through a network of campus corridors and intersections.

Users can adjust the pedestrian population, simulation speed, and corridor rules to explore how different configurations affect pedestrian flow.

The application compares:

- Two-way pedestrian movement
- One-way corridor rules

The simulation then measures changes in travel time, throughput, congestion, and pedestrian movement.

## Features

- Interactive 2D campus map
- Agent-based pedestrian simulation
- Multiple pedestrian agents moving simultaneously
- Configurable pedestrian population
- Adjustable simulation speed
- Two-way and one-way corridor modes
- Congestion and bottleneck visualization
- Congestion-aware pathfinding
- Travel-time analysis
- Throughput measurement
- Corridor-level congestion statistics
- Comparison between corridor configurations
- Interactive simulation controls
- Responsive interface

## Simulation

The simulation represents a synthetic campus as a network of nodes and corridors.

Each pedestrian is assigned a destination and moves through the network using pathfinding while responding to congestion.

The application tracks metrics including:

- Active pedestrians
- Completed trips
- Average travel time
- Throughput
- Overall congestion
- Most congested corridors

The project also provides a comparison between two-way and one-way corridor configurations.

## Pathfinding

The simulation uses graph-based pathfinding to determine pedestrian routes through the campus network.

Routes take congestion into account so that heavily occupied corridors can affect route selection.

## Data

The campus, buildings, pedestrian traffic, and movement patterns are **synthetic demonstration data**.

They do not represent a real university or a real-world campus study.

## Technologies

- HTML5
- CSS3
- JavaScript
- HTML5 Canvas
- Graph modelling
- Dijkstra's algorithm
- Agent-based simulation
- Data visualization
- Responsive web design

## Running Locally

Download or clone the repository and open `index.html` in a modern web browser.

No backend is required.

## Project Purpose

This project explores how interactive simulation and visualization can be used to understand pedestrian movement and identify potential congestion and bottlenecks in a campus environment.

It was developed as an exploration of agent-based modelling, interaction design, pathfinding, and data visualization.

## Important Note

The simulation is a synthetic model intended for experimentation and visualization.

Its results should not be interpreted as measurements or predictions of pedestrian behaviour at a real university.
