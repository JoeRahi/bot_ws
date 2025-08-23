# Mobile Robot Edge Detection Project (bot_ws)

This repository contains a ROS 2 workspace for a mobile robot designed to detect edges and prevent itself from falling off platforms or stairs.

## Features

- Mobile robot platform equipped with edge detection sensors
- Edge detection algorithms to identify drop-offs and prevent falls
- ROS 2 nodes for sensor processing and robot control
- Integration with simulation tools for testing and visualization

## Workspace Structure

- `src/bot_description` — robot description, URDFs, and sensor configurations  
- `src/bot_edge_detection` — edge detection algorithms and ROS 2 nodes

## Usage

### Build the workspace

```bash
colcon build
source install/setup.bash
