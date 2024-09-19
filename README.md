# Project Description:

This project involves optimizing the allocation of smalls (raw materials) for batch production of different blends to maximize monetary gain. The problem is approached using linear programming, specifically the HiGHS solver, to determine the optimal quantity of each smalls to add to each blend while respecting constraints on available quantities and maximum allowable addbacks per batch. While developing this program, I used openAI platforms to generate solutions to particular problems.

## The optimization process involves:

- Defining the cost structure and constraints based on available quantities and batch operations.
- Setting up the linear programming problem with objective function coefficients derived from the profit/loss matrix.
- Applying inequality constraints to ensure the total addbacks do not exceed the available quantities of each smalls.
- Solving the problem to find the optimal addback plan that maximizes the total gain or minimizes the total loss.
- Outputting the optimal allocation plan, total monetary gain/loss, and remaining quantities of each smalls.
- This approach ensures efficient resource utilization while achieving the best possible financial outcome for the production process.
