# Rumor Spread Simulation

## Overview

This project simulates the spread of rumors within a population using various parameters. The program models how rumors propagate through a network of individuals with different levels of skepticism and across multiple generations. The simulation can be run with default parameters or customized values provided by the user.

## About This Project

This simulation was developed as part of the **Bioinformatics course at Bar-Ilan University** during the academic year 2023. It showcases the application of advanced programming techniques, including **multithreading**, **algorithm optimization**, and **graphical visualization**.

## Contributors

- **Reut Lev** (reutlev98)
- **Ye'ela Granot** (yeela8g)

## Features

- **Simulation of Rumor Spread**: Models the spread of a rumor across a population, considering factors like population density, number of generations, and skepticism levels.
- **Customizable Parameters**: Users can adjust parameters such as:
  - `P`: Population density, which influences the likelihood of a rumor reaching more individuals.
  - `L`: Number of generations an individual waits before passing the rumor.
  - `S1`, `S2`, `S3`, `S4`: Different skepticism levels among individuals in the population.
- **Graphical Representation**: The simulation provides a visual display of how rumors spread over time, with different colors representing the state of individuals (believers, non-believers, and rumor spreaders).

## Getting Started

### Prerequisites

- The project is written in C and requires a C compiler to build.
- Ensure `q2.exe` and `main.exe` are in the same directory for execution.

### Running the Simulation

1. **With Default Parameters**:
   - Double-click on `q2.exe` or `main.exe` to run the simulation with preset parameters.
   - These parameters simulate a typical scenario of rumor spread with moderate speed and skepticism.

2. **With Custom Parameters**:
   - Alternatively, the user can input custom values for the parameters directly in the program to simulate different scenarios.

### Parameters Explained

- `P`: Represents the population density. A default value of `75%` is used, which indicates moderate population concentration.
- `L`: Defines the number of generations to wait before an individual spreads the rumor. Default is set to `2`.
- `S1`, `S2`, `S3`, `S4`: Percentages representing different groups with varying levels of skepticism.
- `generation`: Represents the total number of generations the simulation runs for, with a default of `55`.

## Results Analysis

- The simulation provides a statistical summary of the spread of rumors across multiple runs.
- Key outputs include the percentage of believers after the spread and the spread's reach within the population.
- The simulation results show variations based on changes in `P` and `L`, indicating how these factors influence the spread dynamics.

## Visual Representation

- The simulation displays a grid where each cell represents an individual:
  - **Red**: Individuals who have spread the rumor.
  - **Blue**: Individuals who have heard but do not spread the rumor.
  - **White**: Empty cells or individuals not part of the simulation.
    
    ![image](https://github.com/user-attachments/assets/ec808ea0-d781-4e77-9d75-cc785d395a9b)



## Conclusion
This project helps to understand the dynamics of information spread within a population. By adjusting parameters, users can observe how different levels of skepticism and population densities impact the propagation of a rumor.
