# Suspension-System-Design-for-16-Inch-Foldable-Bicycle
This project develops a suspension system for a 16-inch foldable bicycle. Using Creo Parametric for CAD modeling and ANSYS for finite element analysis, we assess structural integrity under various loads. A MATLAB program simulates dynamic performance and optimizes settings for comfort and stability, enhancing urban usability.

## Design & Assembly of model in creo
![image](https://github.com/user-attachments/assets/68128915-f007-49e9-9430-f36382370c46)

The components were assembled within Creo to ensure proper fit and integration with the bicycle’s folding mechanism. Key considerations during assembly included:
i.	Interference Checks: Ensuring no components obstruct the folding action.
ii.	Alignment: Precise alignment to maintain structural integrity and performance.

## Mathematical Modelling
This project employs MATLAB simulations to analyze the suspension system's response to varying forces and conditions. By solving the governing differential equations, we examine how parameters like spring stiffness, damping coefficients, and external forces affect performance, helping to optimize ride comfort, stability, and control.

System Components
Mass (m): Represents the combined mass of the rider and bicycle frame (80 kg), influencing inertia and response to forces.
Spring Constant (k): Set at 1000 N/m, this defines the spring's rigidity and its restoring force.
Damping Coefficient (c): Set to 100 N·s/m, this quantifies the damper's resistance, reducing oscillations for a smoother ride.
Governing Differential Equation
The dynamics of the mass-spring-damper system follow Newton’s Second Law:


Where:
x(t): Displacement

 : Acceleration

F(t): External force
This equation models how the system reacts to external forces, enabling the prediction of performance under various conditions and guiding design enhancements for rider comfort and stability.
