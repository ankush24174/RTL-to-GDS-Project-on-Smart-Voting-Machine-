RTL to GDS Flow

This group project was completed in two phases: RTL-to-DFT implementation and physical design analysis.

Part 1: RTL to DFT
Performed logic synthesis for three constraint scenarios:
Minimum Area
Minimum Time
Intermediate
Created and applied constraint files for each case.
Executed Combinational Equivalence Checking (CEC).
Performed Static Timing Analysis (STA) on the synthesized netlists using the intermediate constraint set.
Completed scan-cell insertion for DFT.


Part 2: Physical Design
Carried out chip planning, including floorplanning and power planning.
Configured the floorplan with:
Aspect ratio: 1
Utilization: 0.8
Core margin clearance
Defined I/O pins manually, and  the design did not include I/O cells.
Used the following inputs for place-and-route:
Netlist
Default view file with physical and technology libraries, Constraint file, MMMC file
Completed power planning by adding a power ring.
Performed placement, Clock Tree Synthesis (CTS), and routing.
Generated the final GDSII file.


Tools Used
RTL Simulation: ncverilog
Logic Synthesis and DFT: Genus
CEC: Conformal
STA: Tempus
Physical Design: Innovus
