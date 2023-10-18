# Optimization Projects Repository
Welcome to the Optimization Projects repository! This collection of projects is guided by the expertise of Professor Stephen J. Wright and primarily implemented in Julia. The projects in this repository focus on solving a variety of optimization problems using optimization solvers such as HiGHS, Ipopt, and Gurobi. 

## Final Project: Apartment Location Optimization
In our final project, we tackled the challenging domain of Mixed-Integer Quadratic Programming (MIQP) and Mixed-Integer Second-Order Cone Programming (MISOCP). We harnessed the power of the Gurobi optimization solver to determine the ideal apartment location in Madison. Our objective was to optimize various factors, including living convenience, proximity to supermarkets, campus, bus stops, and more.

### Problem Statement

Finding the perfect apartment location can be a complex task, as it involves numerous criteria. We aimed to address this issue by formulating it as an optimization problem, with the following objectives:

- **Living Convenience**: We wanted to ensure that the selected location provided a comfortable and convenient living experience. This includes proximity to supermarkets and to the nearest hospital.

- **Proximity to Supermarkets**: Access to groceries and daily necessities is crucial. We considered the distance to supermarkets to ensure that the selected location provided a comfortable and convenient living experience.

- **Campus Proximity**: For students and university staff, proximity to the campus is often a top priority. We aimed to find locations that minimize distance to campus buildings.

- **Bus Stops Accessibility**: Reliable public transportation is a significant factor for many people. We evaluated the accessibility by the distance to the main bus route.

### Gurobi Optimization Solver

Gurobi is a powerful optimization solver renowned for its efficiency and robustness. It is well-suited for solving complex optimization problems like the one presented in this project. By leveraging Gurobi, we were able to find an optimal solution efficiently, considering all the criteria outlined above.

### Usage

To explore our project further and see the implementation in Julia, you can check the associated code files in this repository. 

