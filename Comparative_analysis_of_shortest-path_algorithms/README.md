# Shortest-Path Algorithms Project

This directory contains the **code and report** for the **COMPSCI 2XC3: Algorithms and Software Design** final project. The project presents a comparative analysis of several shortest-path algorithms and was completed collaboratively by **Yanna Lazarova**, **Oriana Rueckert**, and **Lana Zgonjanin**.

## Overview

We developed a Python framework to implement, compare, and evaluate multiple shortest-path algorithms on real-world graph datasets. The project includes theoretical analysis, empirical experimentation, and software design documentation.

## Features

### Implemented Algorithms

The framework supports both **single-source** and **all-pairs** shortest-path algorithms, including:

- **Dijkstra’s Algorithm**
- **Constrained Bellman–Ford**
- **Floyd–Warshall** (implemented in `all_pairs_shortest_path.py`)
- **A\*** with tunable heuristic functions

Each algorithm was evaluated for:

- **Time complexity**
- **Space complexity**
- **Accuracy**

across graphs of varying size and density.

### Software Design & Architecture

The system was built using object-oriented design principles and UML modeling. Key design patterns include:

- **Strategy Pattern** — allows shortest-path algorithms to be swapped interchangeably
- **Adapter Pattern** — integrates A\* into a unified interface
- **Composition** — supports modular, extensible system components

This architecture enables clean experimentation and makes the framework easy to extend with additional algorithms.

