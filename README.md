# TMRCA Simulation

This project simulates how many generations it takes for a population to reach a Most Recent Common Ancestor (TMRCA). The simulation uses random sampling based on Chang’s model.

## Files

- `tmrca_simulation.R` — main simulation script
- `tmrca_results.csv` — results from the simulations
- `tmrca_boxplot.png` — boxplot of the results

## Description

The script runs simulations for population sizes of 1000, 2000, and 4000. For each population size, it tracks how many generations are needed until the population shares one common ancestor.

The results are saved in a CSV file and visualized with a boxplot.

## How to Run

Open R and run:

```r
source("tmrca_simulation.R")
