# CSP-Map-coloring-using-Backtracking

The provided Python code addresses the Constraint Satisfaction Problem (CSP) of map coloring using the Backtracking algorithm. The goal is to assign colors to regions on a map such that no adjacent regions share the same color.

The is_valid function checks whether a given color assignment for a region adheres to the constraint by examining its neighbors in the provided map. The main function, solve_map_coloring, recursively explores possible color assignments for each region. It backtracks when necessary, undoing assignments that lead to conflicts.

The algorithm proceeds by selecting an unassigned region, checking valid colors, and recursively moving forward. If a valid assignment for all regions is found, the color assignment is returned. The code then defines a sample map with regions and their neighbors, as well as a set of colors.

Upon execution, the algorithm attempts to find a valid coloring solution for the map. If successful, it prints the valid coloring assignment; otherwise, it indicates that no valid coloring is possible.

The code demonstrates a backtracking approach to solve the CSP of map coloring, showcasing proficiency in algorithm design, recursion, and constraint handling. The provided example illustrates its application to a specific map scenario.
