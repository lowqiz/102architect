# 102ARCHITECT - Home Planning and Homogeneous Coordinates

## Description
102ARCHITECT is a home planning software tool for an architecture firm, designed to simplify the process of drawing floor plans and applying geometric transformations to objects within the plan. The goal of the project is to develop a program that computes the new coordinates of a point after applying several transformations using homogeneous coordinates.

The transformations include:
- Translation
- Scaling
- Rotation (centered at the origin)
- Reflection over any axis passing through the origin
- Combinations of these transformations

This program will allow architects to easily manipulate points and objects within the design, making the planning process more efficient.

## Features
- **Translation**: Move points along a vector.
- **Scaling**: Zoom in and out by scaling along the x and y axes.
- **Rotation**: Rotate points around the origin (0, 0) by a given angle.
- **Reflection**: Reflect points over any axis that passes through the origin.
- **Combination of transformations**: Apply multiple transformations to points in sequence.

## Usage
To run the program, use the following command:
```bash
python3 102architect.py x y transfo1 arg11 [arg12] [transfo2 arg21 [arg22]] ...
