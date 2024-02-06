# CSP-Map-coloring-using-Backtracking

The Python code tackles the map coloring problem, a classic graph theory challenge where the objective is to color the regions of a map in such a way that no two adjacent regions share the same color. The code employs a backtracking algorithm, which systematically explores different color assignments until a valid solution is discovered or all possibilities have been exhausted.

The is_valid function examines whether a color assignment for a region is permissible based on the colors of its neighboring regions. It iterates through the neighbors of the current region, checking if any neighboring region already has the same color assigned. If such a conflict is found, indicating adjacent regions with the same color, the function returns False, indicating an invalid assignment. Otherwise, it returns True, signifying that the color assignment is valid for the current region.

The solve_map_coloring function is the heart of the solution. It recursively attempts to find a valid coloring for the entire map. Initially, it checks if all regions have been assigned colors. If so, it returns the current color assignment, indicating a valid solution. Otherwise, it selects a region that hasn't been assigned a color yet and tries each available color for that region. For each color choice, it verifies its validity using is_valid. If the assignment is valid, it proceeds recursively, trying to solve the problem with the updated color assignment. If a valid solution is found, it returns that solution. If no valid coloring is found after exploring all possibilities, it backtracks by removing the color assignment for the current region and tries another color.

In the main block, a sample map is provided, representing regions and their neighbors, along with a list of available colors. The solve_map_coloring function is invoked with this data. If a valid coloring is found (coloring is not None), it prints each region along with its assigned color. Otherwise, it prints a message indicating that no valid coloring was found. This code demonstrates how backtracking can efficiently solve the map coloring problem by systematically exploring different color assignments and backtracking when necessary.
