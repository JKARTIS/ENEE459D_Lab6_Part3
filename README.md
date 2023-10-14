## ENEE459D_Lab6_Part3
# Description
In this project, I have two files: Lab6_part3.sv and Lab6_part3.test.sv. Initially, I attempted to run these codes in Vivado. However, I encountered an issue where the randomization of rw_e doesn't work as expected. To address this problem, I decided to run the codes in EDA Playground using the Cadence simulator, where the randomization issue was resolved successfully.

# Files
Lab6_part3.sv: Main SystemVerilog file containing the design logic.
Lab6_part3.test.sv: SystemVerilog testbench file for verifying the functionality of the design.
# Instructions
To reproduce the successful simulation in EDA Playground using the Cadence simulator, follow these steps:

Open EDA Playground (https://www.edaplayground.com/).
Upload the Lab6_part3.sv and Lab6_part3.test.sv files to the platform.
Select the Cadence simulator as the simulation tool.
Run the simulation and observe the results to ensure that the randomization issue with rw_e has been resolved.
# Issues
The randomization of rw_e didn't work as expected in Vivado simulation.
# Simulation Environment
Simulator: Cadence Simulator
Simulation Tool: EDA Playground (https://www.edaplayground.com/)
