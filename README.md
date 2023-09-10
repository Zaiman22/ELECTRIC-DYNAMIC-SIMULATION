# ELECTRIC DYNAMIC SIMULATION
 This is the simulation of the dynamic system of rakata electric. The purpose of this system is to simulate and evaluate the racing strategy of rakata electric.
 Currently this system is created in simulink and matlab but may be changed to python in the future or a python-matlab crossover.

 ## Connecting the datasheet
 Use a lookup table with rpm as x and current, torque as y. We need to extrapolate some data, so i use dynamic lookup table (need to checked). RPM will be treated as inertia so, greater rpm = greater inertias => less torque (need to check).

 ## Added energy calculation
 Just some integration and basic math of current, voltage, and distance but a nice thing to have

 ## future plan
 1. Fit it to ancol (KMHE 2023 track)
 2. Fix the losses and make it dynamic (like raymond's)
 3. check the exterpolation method or change the way to connect datasheet