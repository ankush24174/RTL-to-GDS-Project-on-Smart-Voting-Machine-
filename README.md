RTL to GDS Flow

This group project was completed in two phases: RTL-to-DFT implementation and physical design analysis.

Phase 1: RTL to DFT
Performed logic synthesis for three constraint scenarios:
Minimum Area
Minimum Time
Intermediate
Created and applied constraint files for each case.
Executed Combinational Equivalence Checking (CEC).
Performed Static Timing Analysis (STA) on synthesized netlists using the intermediate constraint set.
Completed scan-cell insertion for DFT.
Phase 2: Physical Design
Performed chip planning, including floorplanning and power planning.
Floorplan configuration:
Aspect ratio: 1
Utilization: 0.8
Core margin clearance
Defined I/O pins manually (no I/O cells in the design).
Inputs to place-and-route:
Netlist
Default view file (physical and technology libraries)
Constraint file
MMMC file
Performed power planning:
Added power rings
Added power rails and straps
Completed:
Placement
Clock Tree Synthesis (CTS)
Routing
Generated final GDSII file.
Tools Used
RTL Simulation: ncverilog
Logic Synthesis and DFT: Genus
CEC: Conformal
STA: Tempus
Physical Design: Innovus
