# Solving an Optimization Problem
### Overview
This project solves a multi-echelon supply chain optimization problem for a logistics network. Using linear programming, the goal was to minimize total transportation costs while meeting fulfillment center demand and adhering to capacity constraints at hubs and focus cities.

### Optimization - Amazon Air case study
- Built a linear programming model (Python, PuLP) with decision variables for multi-leg shipping routes; minimized total cost to ~$199,476 while satisfying all constraints.
- Defined and enforced constraints for hub capacity, focus city capacity, flow balance, and fulfillment center demand to ensure realistic logistics planning.
- Validated the solution by analyzing the solver’s output (optimal status) and confirming that all capacity and demand requirements were met, with active routes and shipment amounts detailed.

### Files
1. README.md - A file describing other files in this repository.

2. D605 Task 1 Final.docx - A Word document file that contains the report for Task 1 (Business Case Analysis).

3. D605 Task 2 Final.docx - A Word document file that contains the report for Task 2 (Identification of the Objective Function and Constraints).

4. D605Task3Final.docx - A Word document file that contains the report for Task 3 (Solve an Optimization Problem).

5. D605Task3Final.ipynb - A Jupyter Notebook file that contains the code for solving an Amazon optimization problem.

6. Amazon Distribution.docx - Contains demand, capacities, and distribution costs.

7. Amazon Air Optimization Solution.docx - Contains the variables, constraints, and objectives.
