# TMRCA Simulation

This project simulates how many generations it takes for a population to reach a Most Recent Common Ancestor (TMRCA). It uses random sampling based on Chang’s model and compares results across different population sizes.

## Files

- `tmrca_simulation.R` — main simulation script
- `tmrca_results.csv` — simulation output
- `tmrca_boxplot.png` — boxplot of the results

## Description

The script runs multiple simulations for population sizes of 1000, 2000, and 4000. For each population size, it tracks how many generations are needed until the population reaches one common ancestor.

The results are saved to a CSV file and shown with a boxplot to make the trend easier to compare.

## How to Run

Open R and run:

```r
source("tmrca_simulation.R")
