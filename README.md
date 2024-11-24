# Stability Analysis of an Inverted Pendulum Using LQR

This project demonstrates the stabilization of an inverted pendulum using the **Linear Quadratic Regulator (LQR)** approach. It showcases modeling, analysis, and control system design for one of the classic problems in control theory.

## Project Overview

The inverted pendulum represents a fundamental problem in dynamics and control theory. The project involves:
- **Modeling**: Representing the dynamics of a cart-pendulum system.
- **Linearization**: Simplifying the nonlinear equations of motion for analysis near the equilibrium point.
- **Control Design**: Implementing an LQR-based state feedback controller for stabilization.

### Key Features
1. **System Modeling**:
   - The dynamics of the inverted pendulum are represented using differential equations and state-space methods.
   - Linearization around the vertical equilibrium point simplifies analysis and controller design.

2. **Linear Quadratic Regulator (LQR)**:
   - Optimizes a quadratic cost function to balance control effort and state error.
   - Provides a robust and efficient solution for stabilizing the pendulum.

3. **MATLAB Implementation**:
   - The project leverages MATLAB for simulation, including state-space modeling and LQR gain calculation.
   - Results are visualized through step response plots for cart position and pendulum angle.

4. **Trade-off Tuning**:
   - Adjusting Q and R matrices in LQR to balance transient performance and control effort.

### Results
- Stabilization of the inverted pendulum with minimal overshoot and fast settling time.
- Improved system performance by tuning LQR parameters.
- Demonstrates the robustness of the control design in achieving desired stability.

### Future Improvements
- Extend the approach to multi-degree-of-freedom systems.
- Integrate sensor noise and actuator limitations for more realistic scenarios.
