# Robotics

A collection of robotics algorithms and autonomous navigation projects implemented from scratch.

## Overview

This directory contains work related to localization, mapping, planning, exploration, and probabilistic robotics.

The primary objective is to build a strong foundation before progressing to research-level topics such as SLAM and autonomous navigation papers.

---

## Localization

Implemented techniques for estimating robot pose under uncertainty.

### Included

* 1D Kalman Filter
* 2D Pose Estimation
* Extended Kalman Filter (EKF)
* Particle Filter Localization

---

## Mapping

Environment representation and occupancy estimation.

### Included

* Occupancy Grid Mapping
* Log-Odds Mapping
* Costmap Generation
* Obstacle Inflation

---

## Planning

Path planning and exploration algorithms.

### Included

* A* Path Planning
* Frontier Detection
* Frontier Clustering
* Information Gain Exploration
* Revisit Penalties
* Uncertainty-Aware Exploration

---

## Experiments

Evaluation and analysis tools.

### Included

* Exploration Metrics
* Experiment Logging
* Visualization Utilities
* Strategy Comparison Framework

---

## Frontier Exploration Project

A complete autonomous exploration simulation combining:

* Particle Filter Localization
* Occupancy Grid Mapping
* Costmap Planning
* A* Navigation
* Frontier-Based Exploration

### Features

* Frontier clustering
* Information gain scoring
* Revisit avoidance
* Frontier memory
* Scan recovery behavior
* Exploration termination conditions
* Experimental evaluation

### Strategies Evaluated

1. Nearest Frontier
2. Information Gain
3. Information Gain + Revisit Penalty
4. Uncertainty-Aware Exploration

---

## Roadmap

### Completed

* Localization
* Mapping
* Planning
* Frontier Exploration

### In Progress

* Research Paper Reproduction

### Planned

* FastSLAM 1.0
* FastSLAM 2.0
* GraphSLAM
* Advanced Motion Planning Papers

---

## Goal

Build a complete understanding of autonomous navigation systems by implementing increasingly sophisticated robotics algorithms from first principles.
