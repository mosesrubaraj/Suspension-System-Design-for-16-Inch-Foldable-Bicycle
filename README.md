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

![formula](https://github.com/user-attachments/assets/68534b72-a21d-402c-93af-8292cb6d5130)

This equation models how the system reacts to external forces, enabling the prediction of performance under various conditions and guiding design enhancements for rider comfort and stability.

## Scenario 1: Step Input Force
Description: A 50 N step force is applied at t=1 second to test stability.

Objective: Evaluate the suspension’s ability to quickly regain stability and minimize oscillations after sudden shocks, ensuring a stable, comfortable ride.

Results: The system demonstrated efficient damping, rapidly returning to equilibrium with minimal oscillation, effectively restoring stability after disturbances and ensuring rider comfort and control.

![image](https://github.com/user-attachments/assets/10001f27-44d0-411d-b4b1-2d93555b2b4c)

## Scenario 2: Damped Sinusoidal Force
Description: A damped sinusoidal force simulates continuous road vibrations.

Objective: Assess the suspension’s ability to absorb and dissipate energy, minimizing vibration impact for a smooth ride.

Results: The system effectively managed continuous vibrations, maintaining stability and rider comfort over extended dynamic conditions, showcasing efficient energy absorption and damping.

![image](https://github.com/user-attachments/assets/fa6df597-fe43-44d0-bc16-af289eb9d10a)

## Scenario 3: Impulse Force
Description: A 50 N impulse applied at t=1 second.

Objective: Assess maximum displacement and time to stability, focusing on shock absorption and stability recovery.

Results: The system managed the impulse with minimal peak displacement and rapid stabilization, demonstrating strong shock absorption and ensuring rider comfort and control in dynamic situations.

![image](https://github.com/user-attachments/assets/3f9c5643-3d1e-4a53-8610-e3194febd78d)

## Scenario 4: Random Force
Description: Simulates unpredictable terrain with random force inputs.

Objective: Test stability and control under unpredictable forces, ensuring reliable performance in real-world conditions.

Results: The suspension system maintained stability and control, effectively managing random fluctuations. This demonstrates its capability to deliver a smooth, dependable ride even on varied terrains.

![image](https://github.com/user-attachments/assets/33c2c76f-8dff-434e-938b-e3801919b9cc)

## Scenario 5: Higher Damping
Description: Damping coefficient increased to 200 N·s/m.

Objective: Assess the impact of higher damping on oscillation control and stability.

Results: Increased damping reduced oscillation amplitude but slowed system response, indicating a trade-off between stability and speed of recovery. Enhanced damping improves stability but may affect rider comfort by prolonging balance restoration.

![image](https://github.com/user-attachments/assets/4ed1c55b-069c-4f5f-89ad-6411361b4acb)

## Scenario 6: Lower Spring Constant
Description: Spring constant reduced to 500 N/m.

Objective: Evaluate the effects of a softer suspension on comfort, stability, and responsiveness.

Results: The system showed increased displacement, improving ride comfort but slightly reducing stability. A more flexible suspension absorbs shocks better, but may compromise control on uneven surfaces or during movement.

![image](https://github.com/user-attachments/assets/fe94fa54-319d-46b9-b8fe-5f3390cfab29)

## Scenario 7: Light Rider
Description: Rider mass reduced to 60 kg.

Objective: Assess effects of reduced mass on dynamics, stability, and responsiveness.

Results: Reduced mass improved stability and responsiveness but increased vibrations due to decreased damping. This suggests that while a lighter setup enhances agility, it may reduce ride comfort by amplifying vibrations.

![image](https://github.com/user-attachments/assets/b7ccfc2b-92c6-4dc6-9785-0e49b6f93876)

## Scenario 8: Heavy Rider
Description: Rider mass increased to 100 kg.

Objective: Assess the impact of higher mass on stability, inertia, and damping.

Results: Increased mass improved stability but slowed response times, indicating a need for enhanced damping to maintain control and effective shock absorption in heavier setups.

![image](https://github.com/user-attachments/assets/e7954c8e-caf2-4472-a48a-d6a73982dd17)

## Scenario 9: Nonlinear Damping
Description: Introduce nonlinear damping.

Objective: Assess the impact of variable damping on shock handling, oscillation control, and stability.

Results: Nonlinear damping improved performance across varied conditions, enhancing adaptability and control. This approach supports stability and comfort in unpredictable environments, showing promise for real-world applications.

![image](https://github.com/user-attachments/assets/5dd64a12-c879-4f60-a48c-d4f296040aae)


## Scenario 10: Road Profile
Description: Simulate urban terrain with bumps and potholes.

Objective: Assess suspension efficiency on standard urban obstacles for rider comfort and control.

Results: The system handled road irregularities effectively, maintaining rider comfort and stability. This demonstrates its capability to manage common urban obstacles, providing a smooth and controlled ride in varied real-life conditions.

![image](https://github.com/user-attachments/assets/94f807bd-9300-4965-9d33-b6995e3b56b9)

## Scenario 11: Temperature Effects (Cold Conditions)
Description: Increased stiffness and damping for cold conditions.

Objective: Assess suspension performance in cold temperatures, focusing on stiffness, damping, and ride quality.

Results: Increased rigidity improved control but reduced displacement, resulting in a less comfortable ride. This shows that while higher stiffness enhances stability, it may compromise comfort, especially in cold weather or on uneven terrain.

![image](https://github.com/user-attachments/assets/63bbf76d-a820-43d0-b3df-dcfb584ba986)

## Scenario 12: Temperature Effects (Hot Conditions)
Description: Decreased stiffness and damping for hot conditions.

Objective: Assess the impact of reduced material properties on shock absorption, stability, and longevity.

Results: Increased displacement improved comfort but required careful adjustments to maintain stability. Balancing flexibility and control is crucial, as too much flexibility may compromise stability and performance.

![image](https://github.com/user-attachments/assets/972e8cbb-b726-4f0c-9c5b-3bd15362d2a6)

## Structural Analysis in ANSYS
The ANSYS simulation assesses the suspension system's structural integrity by analyzing stress and strain under various loading conditions, ensuring its durability and reliability.

### Meshing and Model Setup:

Mesh Generation: Refined elements applied to critical areas for accuracy.
Material Properties: Based on standard values like Young's modulus, Poisson's ratio, and density.
Boundary Conditions: Constraints simulate real-world conditions.

![image](https://github.com/user-attachments/assets/b0d74e3a-bcab-43b1-b383-595f14cff71c)

### Initial Load Scenarios:

Fixed Support: Applied at rear dropouts and bottom bracket.
Combined Loads:
Rider weight: 400 N (saddle), 200 N (handlebar), 200 N (pedals)
Pedaling force: 200 N downward at each pedal
Braking force: 300 N horizontally at front brake mounts
Road impact: 500 N vertically at front fork dropouts

![image](https://github.com/user-attachments/assets/0ca645fc-bf3b-4913-a317-c4e50b1f98d8)

## Result Analysis
### 6.1 Introduction
This chapter presents the results of MATLAB dynamic simulations and initial ANSYS structural analysis, focusing on the suspension system's performance under different conditions. The key metrics include displacement, velocity, stress distribution, and structural integrity, providing insights into potential areas for improvement to enhance system performance and durability.

### 6.2 Dynamic Simulation Results
The MATLAB simulations assess the suspension's response to various forces and operating scenarios, focusing on displacement, velocity, and stability. These results help identify the system's ability to absorb shocks and maintain control, ensuring a smooth ride in different conditions.

#### 6.2.1 Displacement and Velocity Analysis
The displacement and velocity analysis evaluates the suspension’s ability to absorb shocks and maintain stability.

Step Input Force: The system rapidly stabilized after the force, showing effective impact absorption and quick recovery to equilibrium.
Damped Sinusoidal Force: The system maintained stable displacement and velocity, effectively handling continuous oscillations.
Impulse Force: The system absorbed the shock efficiently and quickly returned to stability with minimal oscillation.
Random Force: The system stabilized under random inputs, showing adaptability to unpredictable terrain.

#### 6.2.2 Effect of Damping and Spring Constants
Different damping coefficients and spring constants were tested to analyze their impact on ride comfort, stability, and responsiveness.

Higher Damping: Increased damping reduced oscillations but slowed response times. A balance between vibration reduction and system agility is necessary.
Lower Spring Constant: Reduced spring stiffness improved comfort but compromised stability. Additional stabilization mechanisms are required for control.

#### 6.2.3 Rider Mass Impact
Simulations explored the effect of rider mass on system performance, showing that lighter riders improved response times and stability, while heavier riders increased inertia, slowing system response and requiring higher damping for control.

Light Rider: Faster response and improved stability due to reduced inertia, though damping adjustments may be needed for optimal performance.
Heavy Rider: Increased inertia required higher damping to maintain stability and ride comfort.

#### 6.2.4 Nonlinear Damping and Temperature Effects
Nonlinear damping and temperature fluctuations were investigated to assess their impact on shock absorption and system stability.

Nonlinear Damping: Enhanced adaptability to various forces, improving comfort and control across different terrains.
Road Profile: The system efficiently handled bumps and potholes, providing a comfortable and stable ride in urban settings.
Cold Conditions: Increased rigidity improved stability but reduced shock absorption, compromising comfort.
Hot Conditions: Increased flexibility improved comfort but might compromise stability, requiring adjustments to maintain control.

### 6.3 Structural Analysis in ANSYS
The initial structural analysis in ANSYS assessed stress distribution and the suspension's structural integrity under operational loads, ensuring its durability and reliability in real-world settings.

#### 6.3.1 Mesh Quality and Validation
The mesh was refined in critical areas to ensure accurate stress and strain measurements, providing a solid basis for structural analysis.

### 6.4 Conclusion
The MATLAB simulations demonstrated the suspension system's effective shock absorption and stability under varying conditions. The ANSYS structural analysis validated the system’s design, confirming its suitability for real-world use. Combined, these findings provide a strong foundation for further refinement of the suspension system for urban cycling applications.

