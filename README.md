# Stage-Simulation-in-Python
The project establishes a visual manifestation of a performance stage for the rock star band known as "Spinal Tap." We use Python and its libraries, such as NumPy and Matplotlib, to yield an interactive plot that demonstrates the stage arrangement, lighting effects, smoke machines, and the band’s props.

## Dependencies
- Python 3
- NumPy
- Matplotlib

## Features
- Lights: The program creates five instances of the Light class with different positions, directions, intensities, and colors. The lights are represented as quiver plots and their colors change over time.

- Smoke Machine: The program creates a smoke machine instance with a position, direction, intensity, and diffusion type. The smoke machine is represented as a filled circle, and smoke is simulated using a smoke grid.

- Band: The program creates a band object with a position and shape. The band is represented as a filled shape on the stage, and its position can be updated.

## Getting Started
To run the program, make sure you have Python and the required dependencies installed. You can install the dependencies using the following command:

## Customization
- Lights: You can customize the properties of the lights by modifying the `Light` class instances in the code. You can change their positions, directions, intensities, and colors.

- Smoke Machine: You can customize the properties of the smoke machine by modifying the `SmokeMachine` class instance in the code. You can change its position, direction, intensity, and diffusion type.

- Band: You can customize the position and shape of the band by modifying the `Band` class instance in the code. You can update the band's position using the `update_position` method.

## License
This program is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
