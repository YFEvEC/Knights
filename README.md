
**Project Name:** Knights Partial Domination

**Project Description:**

The Knights Partial Domination project focuses on solving the classic Knights problem using linear programming. The goal is to determine the maximum number of knights that can be placed on a chessboard while ensuring that knights of different colors do not attack each other and that each color has an equal number of knights. The project utilizes LP (Linear Programming) to optimize the placement of knights on various board sizes.

**Key Features:**

- Mathematical modeling of the Knights problem.
- Generation of LP input files for different board sizes and configurations.
- Use of LP solver to find optimal solutions.
- Visualization of board configurations.

**Project Structure:**

The project is organized as follows:

- `knights.tex`: LaTeX document containing the mathematical modeling of the problem.
- `lp_input_generator.R`: R script for generating LP input files.
- `results.txt`: Sample LP solver results.
- `images/`: Directory containing visual representations of board configurations.

**Usage:**

To use this project, you can modify the board size and other parameters in the `lp_input_generator.R` script and generate LP input files. Then, you can use an LP solver to find the optimal solutions. Visual representations of the board configurations are available in the `images/` directory.

For detailed information, please refer to the LaTeX document (`knights.tex`) for the mathematical model and the R script (`lp_input_generator.R`) for LP input file generation.

**Note:**

This project provides a mathematical and computational approach to solving the Knights problem and can be customized for different board sizes and configurations.

