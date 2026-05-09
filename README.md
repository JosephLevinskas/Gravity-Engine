# Gravity Engine

A C++ physics simulation project for modeling gravitational motion in 3D space.

The goal of this project is to build a small gravity engine from scratch, beginning with simple motion and eventually expanding into a solar-system simulator where bodies interact through Newtonian gravity.

This project is being built as a learning-focused systems project. The emphasis is on understanding the physics, math, simulation design, and C++ architecture instead of relying on large external libraries.

## Goals

- Simulate motion in 3D space
- Model gravity between multiple bodies
- Build toward a working Sun, Earth, and Moon simulation
- Support arbitrary bodies with mass, radius, position, and velocity
- Experiment with numerical integration methods
- Eventually render the simulation visually
- Keep the core physics engine independent from rendering

## Current Focus

The first milestone is simple 3D motion:

```text
position = position + velocity * dt