# Cathode Ray Tube Project

This project implements a cathode ray tube (CRT) using OpenGL and C++. The CRT simulation includes drawing the outer body and various parts of the CRT, as well as tracing the electron beam based on input coordinates.

## Project Steps

The project is divided into the following steps:

1. **Drawing the outer body and parts of the CRT:** In this step, the outline and inner parts of the CRT are drawn using OpenGL functions and algorithms. The animation is displayed at 60 frames per second using the timer function.

2. **Tracing the electron beam:** This step involves asking for coordinates of the point to be lit on the CRT screen. The electron beam is plotted from the filament of the electron gun to the end of the deflecting plates, and then from the end of the deflecting plates to the specified point. The process of plotting the electron beam is explained further in the code comments.

## Code

The code provided in this repository is written in C++ and utilizes the OpenGL library. It includes functions for drawing the outer body, parts of the CRT, and the electron beam. The code is well-commented to explain the different steps and algorithms used.

## How to Run

To run the project, follow these steps:

1. Ensure you have the necessary dependencies installed, including OpenGL and the required C++ compiler.

2. Clone the repository to your local machine

3. Compile the source code using: 'g++ main.cpp -o crt -lGL -lGLU -lglut'

4. Run the executable file generated

## Contributions

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to modify and distribute the code as per the terms of the license.
