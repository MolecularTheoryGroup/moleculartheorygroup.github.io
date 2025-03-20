---
title: "Bondalyzer: Examples"
excerpt: "Example applications of Bondalyzer for chemical bond analysis"
category: bondalyzer
collection: research-tools
permalink: /research-tools/bondalyzer/examples/
date: 2023-01-02
---

# Bondalyzer Examples

This page provides examples of how to use Bondalyzer for various types of chemical systems.

## Example 1: Water Molecule Analysis
```python
import bondalyzer as bz

# Load water molecule
water = bz.load_molecule("H2O.xyz")

# Perform electron density analysis
density = bz.calculate_density(water, method="DFT", functional="B3LYP")

# Find bond critical points
bcps = bz.find_critical_points(density, type="bond")

# Visualize results
bz.plot_density_with_bcps(density, bcps)
```

## Example 2: Transition Metal Complex
...

## Example 3: Hydrogen Bonding Network
...
