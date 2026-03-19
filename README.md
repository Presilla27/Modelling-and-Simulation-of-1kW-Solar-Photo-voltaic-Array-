# Modelling-and-Simulation-of-1kW-Solar-Photo-voltaic-Array-

## AIM
To model and design a 1kW solar photovoltaic system using MATLAB Simulation and obtain the 
current, voltage, power values and solar PV characteristics curves.

## APPARATUS REQUIRED
MATLAB 2021 or above

## PROCEDURE
1. Open MATLAB
2. From Simulink library browser, pick the following components
a. solar cell
b. constant
c. PS converter, S converter
d. Current sensor, voltage sensor
e. Variable resistor
f. Ramp
g. Scope, XY graph
3. Connect the thirty-six solar cells in series with common irradiation and make it as a 
subsystem to form a panel.
4. Form similar six panel and connect them in series to form an array with single irradiance 
input.
5. Create a subsystem for the six panels.
6. Connect the constant block with a value of 687 to the irradiance input through PS 
converter.
7. From the output of the solar array connect a current sensor in series to the positive 
terminal and voltage sensor across the terminals.
8. Connect a variable resistor across the solar pv array terminal.
9. Connect a ramp signal to the variable resistor through the PS connector.
10. Using Simulink converter, connect the terminals of the current sensor and voltage sensor 
to the scope to record the graph.
11. Use divide block and convert to multiplication operation and multiply the current and 
voltage outputs to get the power output.
12. Set the minimum and maximum range in X-Y graph to obtain the IV and PV 
characteristics.

## SIMULATION DIAGRAM
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6050f3e3-975a-4269-8ef1-f72b0205a1c3" />
<img width="1753" height="472" alt="image" src="https://github.com/user-attachments/assets/8994c3f2-8135-40b0-900d-93ad3f0e39f2" />
<img width="1338" height="864" alt="image" src="https://github.com/user-attachments/assets/61a5f17c-5372-49e1-97d1-01b71e52f6b6" />
<img width="637" height="642" alt="image" src="https://github.com/user-attachments/assets/79efeee9-d375-4448-86b3-f9229c48a88d" />

## OUTPUT GRAPH
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0b9171a0-3393-4d96-947c-ddfc12155fe2" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/5932ee59-0e8c-441b-ab71-8bbd72000966" />
<img width="1917" height="1079" alt="image" src="https://github.com/user-attachments/assets/9938482b-4e02-4104-b699-07694aca016c" />

## OUTPUT TABLE







