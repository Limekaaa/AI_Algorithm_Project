# AI_Algorithm_Project
School project about optimization with different algortihm. The goal was to explore and implement approaches that could lead to good results. 
The explored algorithms was mainly genetic algorithm, local search algorithms and reinforcement learning using pytorch.

Description: 

This project focuses on optimizing the production of biscuits for Christmas using a single roll of dough. The goal is to maximize profit while adhering to constraints related to dough usage and defect thresholds.

## Key Details

### Dough Roll
- **Length**: Rectangular roll of predefined length (`LENGTH`).
- **Defects**: 
  - Located at specific positions (`x`).
  - Classified into types (e.g., 'a', 'b', 'c').

### Biscuits
- Can be produced in various sizes with:
  - **Size**: A specific length (1D dimension).
  - **Value**: The price or profit value.
  - **Defect Thresholds**: Maximum defects of each class the biscuit can contain.

## Problem Constraints

### Valid Biscuit Placement
- Biscuits must:
  - Be placed at integer positions.
  - Not overlap with other biscuits.
  - Meet defect thresholds for their covered positions.
- Total size of all biscuits must not exceed the dough roll's length.

### Solution Value
- Calculated as:
  - **Sum of Biscuit Values**: The total value of all placed biscuits.
  - **Penalty for Waste**: A penalty of −1 per unused position on the roll to reflect material waste.

## Objective
The project aims to arrange biscuits along the dough roll to maximize total value while minimizing waste and adhering to defect constraints.
