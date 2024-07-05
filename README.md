# CSP-Map-coloring-using-Backtracking

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contribution](#contribution)


## Project Overview
The Python code tackles the map coloring problem, a classic graph theory challenge where the objective is to color the regions of a map in such a way that no two adjacent regions share the same color. The code employs a backtracking algorithm, which systematically explores different color assignments until a valid solution is discovered or all possibilities have been exhausted.


## Installation
This project requires Python 3.12.1 or later.
To set up the project:
1. Ensure Python 3.12.1 or a later version is installed on your system. You can download Python from [python.org](https://www.python.org/downloads/).
2. Clone or download the repository to your local machine.

            git clone https://github.com/jaiswalchitransh/CSP-Map-coloring-using-Backtracking.git

3. Open the project in your preferred Python environment (e.g., IDE or terminal).
4. Modify the `map`, `regions`, and `colors` variables in the main block of the `map_coloring.py` script according to your map and color choices.
5. Run the script (`csp_map_coloring.py`) and observe the output to see the valid coloring of regions.


## Usage
Modify the `map`, `regions`, and `colors` variables in the main block according to your map and color choices.

Run the script:

            python csp_map_coloring.py
  
Observe the output to see the valid coloring of regions.


## Features
- **Backtracking Algorithm**: Utilizes a backtracking approach to systematically explore and find valid colorings for the map.
- **is_valid Function**: Checks whether a color assignment for a region is valid based on its neighbors.
- **solve_map_coloring Function**: Recursively attempts to find a valid coloring for the entire map.
- **Main Block**: Provides a sample map with regions and their neighbors, along with a list of available colors, demonstrating how the solver works.


## Contribution
I, **Chitransh Jaiswal** developed this Project Individually. I was responsible for all aspects of the project, including design, development, testing, and documentation.
Contributions to improve the efficiency, readability, or functionality of the code are welcome. To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Create a new Pull Request.

Please ensure your contributions adhere to the coding standards and follow the existing style and structure.

---

Thank you for your interest in the CSP Map Coloring using Backtracking!
