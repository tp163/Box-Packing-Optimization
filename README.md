# Box Packing Optimization

A 3D bin-packing optimization project that arranges heterogeneous boxes inside a container while considering placement constraints, spatial efficiency, and physical behavior. The project combines a Python-based packing algorithm with Blender to visualize the packing arrangement and simulate box interactions using rigid-body physics.

Project Overview

This project implements a greedy 3D bin-packing algorithm to determine how boxes of different dimensions can be efficiently arranged within a container. It uses volume-based sorting, extreme-point placement, and six-axis orientation permutations to explore possible placements while validating container boundaries and collisions.

The packing results are visualized in Blender through procedural object generation and rigid-body physics simulation, providing a visual representation of the packing arrangement and box behavior.

Key Features

Greedy 3D Bin-Packing Algorithm: Arranges boxes using volume-based sorting and extreme-point placement strategies.

Orientation Optimization: Evaluates six possible axis orientations for boxes to identify feasible placements.

Constraint Validation: Checks collisions, container boundaries, and placement feasibility.

Space Utilization Analysis: Calculates volume utilization to evaluate packing efficiency.

3D Visualization: Generates box and container objects programmatically in Blender.

Physics Simulation: Simulates box interactions using rigid-body physics with configurable friction, damping, and staggered object activation.

Technologies Used

Python

Blender

Blender Python API (bpy)

itertools

Rigid Body Physics

## Project Visualization
<img width="1768" height="851" alt="image" src="https://github.com/user-attachments/assets/9f4ff2e3-58fd-4277-8100-f0a39e494d30" />

<img width="1488" height="825" alt="image" src="https://github.com/user-attachments/assets/8e425f9b-21f0-4b23-bf5f-31340d6b3c3b" />


Blender Project File

The original Blender project file (.blend) exceeds GitHub's standard file upload limit of 100 MB. Therefore, the Blender file is not included in this repository. Instead, images and screenshots of the project are provided to showcase its visualization and simulation results.

