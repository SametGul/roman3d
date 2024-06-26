# Roman3D: 3 DOF Planar Robotic Manipulator

## Overview

This repository contains all the necessary components for constructing and operating a 3-DOF planar direct drive robotic manipulator. The project includes:

* A CAD model design of the robot
* Embedded code for the data acquisition card
* Circuit design for the data acquisition card
* A MATLAB project template

The schematic of this experimental setup is shown in the figure below. The control algorithms are implemented in MATLAB/Simulink, referred to as the control unit in the diagram. The custom data acquisition unit gathers encoder signals from robot and and send them to the control unit.  It also receives control signals from the control unit and transforms them into voltages, which are then amplified before given to the robot. The experiments run in real-time with a sampling rate of up to 10 kHz.

![Experimental Setup Schematic](figs/setup.png)

## Contents

- `CAD/`: Contains the CAD model files for the robot.
- `EmbeddedCode/`: Contains the embedded code for the data acquisition card.
- `CircuitDesign/`: Contains the circuit design files for the data acquisition card.
- `MATLABProject/`: Contains the MATLAB project template for running the experiment.

## Prerequisites

### Hardware

- [List the required hardware components]
- Data acquisition card
- [Any other required components]

### Software

- MATLAB (version X.X or later)
- [Any additional software dependencies]

## Setup Instructions

### Hardware Setup

1. Assemble the robot using the provided CAD model files (`CAD/` directory).
2. Construct the data acquisition card according to the circuit design files (`CircuitDesign/` directory).
3. Connect the data acquisition card to the robot and any other necessary components.

### Software Setup

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/robotic-experiment-setup.git
    cd robotic-experiment-setup
    ```

2. Open the MATLAB project template located in the `MATLABProject/` directory.
3. Load the embedded code onto the data acquisition card using the instructions provided in the `EmbeddedCode/` directory.

## Usage

1. Power on the robot and data acquisition card.
2. Open MATLAB and navigate to the project template.
3. Follow the instructions in the MATLAB project to run the experiment.

## Documentation

For detailed documentation on each component, refer to the following:

- [CAD Model Documentation](./CAD/README.md)
- [Embedded Code Documentation](./EmbeddedCode/README.md)
- [Circuit Design Documentation](./CircuitDesign/README.md)
- [MATLAB Project Documentation](./MATLABProject/README.md)
