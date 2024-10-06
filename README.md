# Operations Research: Linear Programming Solutions

## Overview

This repository contains a collection of four linear programming problems solved using the **Simplex Method** and **Graphical Methods**. The problems illustrate different optimization scenarios, demonstrating various approaches to finding optimal solutions in Operations Research.

# Linear Programming Problem Set

## Problem 1: Graphical Solution and Simplex Method
- **Objective**: Solve a linear program graphically and using the Simplex Method.
- **Task**: Draw the feasible region and plot 4 level curves. Identify the vertices of the feasible region. 
- **Solution Approach**: 
  - Use the graphical method to move from vertex to vertex in the feasible region and identify the optimal solution.
  - Implement the Simplex Method, showing the sequence of tableaus and the basic solutions.

## Problem 2: Investment Portfolio Optimization
- **Scenario**: A funds manager receives $100,000 for investment in blue-chip stocks (BLUE), tech stocks (TECH), and high risk/high yield stocks (HRHY).
- **Constraints**:
  1. No more than 2,500 shares should be purchased in total.
  2. The amount of BLUE stocks purchased must exceed the total of TECH and HRHY stocks purchased.
  3. HRHY stocks purchased should not exceed 10% of the BLUE stocks purchased.
- **Objective**: Maximize the expected return on investment, considering the cost per share and returns for each type of stock.
- **Solution Approach**: Formulate and solve the linear program using the Simplex Method. Report the sequence of tableaus and the final basic solution.

## Problem 3: Parameterized Linear Program
- **Scenario**: Solve a linear program with an objective function parameterized by a constant.
- **Tasks**:
  1. Use the Simplex Method to solve the initial problem for a fixed value of the parameter.
  2. Analyze how varying the parameter affects the optimality of the initial solution.
  3. Determine the range of parameter values for which the initial solution remains optimal.
- **Solution Approach**: Use Gaussian pivoting and sensitivity analysis to report the range of parameter values for which the optimal solution changes.

## Problem 4: Diet Optimization Problem
- **Scenario**: Minimize daily calorie intake from a diet of black beans, wild rice, and spinach while meeting the minimum recommended daily allowances (minRDA) for a collection of nutrients.
- **Objective**: Set up and solve the linear program to determine the quantity of each food item that meets nutritional constraints with minimum calorie consumption.
- **Solution Approach**: Solve using both the Simplex and Graphical methods, showing intermediate tableaus and basic solutions.

## Methods Used

- **Simplex Method**: Used for multi-variable linear programming problems to find the optimal solution by pivoting through different feasible basic solutions.
- **Graphical Method**: Applied to two-variable problems to graphically visualize the feasible region and determine the optimal solution.
