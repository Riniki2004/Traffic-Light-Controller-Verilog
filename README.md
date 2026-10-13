Traffic Light Controller Using Verilog HDL

Overview

This project implements a T-junction traffic light controller using Verilog HDL and a Moore Finite State Machine (FSM). The controller manages traffic signals for multiple approaches through a predefined sequence of states, ensuring organized signal transitions and controlled traffic movement.

The design demonstrates fundamental concepts of digital logic design, sequential circuits, state-based control, and RTL implementation.

Objectives

- Design a traffic light controller using Verilog HDL.
- Implement a Moore FSM for deterministic traffic signal sequencing.
- Develop state transition and output logic using sequential and combinational logic.
- Implement timing control for green, yellow, and red signal intervals.
- Verify the controller's functional behavior using a Verilog testbench.

Key Features

1. Moore FSM-Based Architecture

The traffic controller uses a finite set of states to determine the active traffic signals. Outputs depend on the current state, providing structured and predictable control behavior.

2. Multi-Direction Traffic Management

The controller is designed to coordinate traffic across multiple approaches at a T-junction, including the main-road and side-road movements defined in the implementation.

3. Timing-Based Signal Sequencing

Configurable or predefined timing intervals control the duration of each signal phase, including green and yellow transitions.

4. Simulation-Based Verification

A Verilog testbench can be used to examine state transitions, signal sequences, and timing behavior under simulation.

Technologies Used

- Hardware Description Language: Verilog HDL
- Design Methodology: Register Transfer Level (RTL)
- Control Architecture: Moore Finite State Machine
- Verification: Verilog testbench
- Simulation Tool: AMD Xilinx Vivado, if used for this implementation
- Version Control: Git and GitHub

Design Methodology

1. Define the traffic signal states and their corresponding outputs.
2. Develop the FSM transition logic to determine the next state.
3. Implement timing logic to control the duration of each traffic phase.
4. Assign red, yellow, and green outputs according to the current state.
5. Simulate the design and verify the expected signal sequence.

Verification Objectives

The design should be tested for:

- Correct state transitions.
- Expected green and yellow phase durations.
- Safe sequencing between conflicting traffic movements.
- Correct signal outputs for each FSM state.
- Proper initialization and reset behavior, if implemented.

Applications

- Digital traffic signal control systems.
- FSM-based embedded control applications.
- Learning RTL design and sequential logic.
- FPGA-based digital system prototyping.

Future Improvements

- Add configurable signal timing parameters.
- Extend the controller to support sensor-based traffic prioritization.
- Improve verification with assertions and additional test scenarios.
- Implement the design on an FPGA development board.
- Analyze timing and hardware resource utilization after synthesis.

Author

Riniki Devi

GitHub: "Riniki2004" (https://github.com/Riniki2004)

---

An educational digital design project demonstrating Moore FSM architecture, RTL development, and simulation-based verification using Verilog HDL.
