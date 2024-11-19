# Interactive Bisection Method with Neumorphic Interface

This project is an interactive application built using Python's Tkinter that visualizes the Bisection Method for finding roots of a function. It is designed with a Neumorphic interface style and includes error analysis with 2D and 3D visualizations.

## Project Overview

The application allows users to:
- Input a mathematical function to find its root using the Bisection Method.
- Specify the interval \([a, b]\) to locate the root.
- Visualize the iterative steps on a 2D plot and a 3D surface plot.
- Analyze error metrics such as absolute and relative errors for each iteration.

## Features

- **Neumorphic Interface**: Provides a modern, soft UI design.
- **2D Plot**: Displays the function curve and iterative vertical lines for each midpoint calculation.
- **3D Plot**: Shows the function's surface with markers indicating the iterative steps.
- **Detailed Error Analysis**: Shows absolute and relative errors at each step.
- **Interactive GUI**: Simple interface for input and visualization.

## Project Demo

### 2D Visualization of Bisection Method
![bisection1](https://github.com/user-attachments/assets/9cd88fbe-f073-4f14-b840-35cf129f4082)
### 3D Visualization of Function with Iterations
![bisection2](https://github.com/user-attachments/assets/3b436408-f641-457e-9e10-0f75798063ea)

## How to Run

1. **Clone the repository** or download the project files.
2. Ensure Python 3.x is installed.
3. Install the required Python packages:
   
   ```bash
   pip install numpy
   pip install matplotlib


5. Run the script:
   
   ```bash
   python bisection_app.py

## Dependencies
1. Tkinter: Used for creating the graphical user interface.
2. NumPy: Facilitates mathematical operations and array management.
3. Matplotlib: Utilized for rendering 2D and 3D visualizations.

## Usage Instructions
1. Enter the function f(x) (e.g., x**3 - 6*x**2 + 4*x + 12) in the provided input box.
2. Provide the interval [a,b] for the method to search for the root.
3. Review the plotted results in the 2D and 3D visualization areas.
4. An error analysis report is displayed in a popup with detailed iteration results.

## Example Output
1. 2D Visualization: Shows the function f(x) with the midpoints marked as red dashed lines.
2. 3D Visualization: A surface plot that illustrates the function with red markers for iteration points.

## Code Highlights
### Bisection Method ImplementationThe core logic iteratively finds the root by halving the interval:
     ```bash
       def bisection_method(func, a, b, tol=1e-5, max_iter=100):
       iterations = []
       errors = []
       ...
       return c, iterations, errors
       
## Neumorphic Design
The interface uses a combination of dark and light shades for a Neumorphic look:
1. Background color: #2f3542
2. Widget color: #a4b0be

## License
This project is licensed under the MIT License.

## Contact
For any questions or feedback, please contact Chayon Das at daschayon26@gmail.com.

