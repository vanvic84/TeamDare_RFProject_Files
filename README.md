
# Team Dare – ECE 09363: Modules in ECE

Contributors: Darrence Diza, Sarah Ely, Victoria Van

Software Used: ANSYS HFSS

**Overview**
This project explores the simulation and analysis of RF transmission line structures using ANSYS HFSS. It includes the modeling and analysis of:

	Part 1: A 50Ω microstrip transmission line (Modules_NewPart1.aedt)

	Part 2: A stepped-impedance transmission line (SteppedImpedanceLine.aedt)

	Part 3: A quad hybrid coupler operating at 2.45 GHz (Modules_Project1_Part3.aedt)

The project applied RF transmission line theory to real-world design scenarios and evaluated key performance parameters, including impedance matching, bandwidth, return loss, coupling, and port isolation. This folder contains simulation files and documentation for a three-part RF design project using ANSYS HFSS. The project involves the design, simulation, and analysis of different RF structures focused on transmission line behavior and power division.


**Project Structure**

**Part 1: 50Ω Microstrip Transmission Line**

File Name: Modules_NewPart1.aedt 

Goal: Establish a matched line to a 50Ω system.

Simulations:

	S-parameter plots

	Smith charts

	Input impedance and VSWR

E-field, H-field, and current distribution

Result: Strong impedance match, low return loss, stable mode propagation.



**Part 2: Stepped-Impedance Transmission Line**
Goal: Analyze impedance transitions (25Ω–50Ω–75Ω) and bandwidth impact.

File Name: SteppedImpedanceLine.aedt

Simulations:

	S11 and S21 magnitude plots
	
	Smith chart analysis
	
	Current distribution

Result: Effective broadband performance from 1–6 GHz with low reflection and good transmission.


**Part 3: Quad Hybrid Coupler**

File Name: **Modules_Project1_Part3.aedt**

Goal: Design a 3 dB, 90° coupler at 2.45 GHz with power splitting and port isolation.

Simulations:

	Full S-parameter analysis
	
	E-field distribution
	
	Power division and phase behavior

Result: Near-ideal behavior with S21/S31 ≈ -3 dB and S41 ≪ -30 dB. Confirms isolation and phase quadrature.


**Key Learnings**


Transmission line behavior critically impacts system performance at high frequencies.

Impedance matching is essential for minimizing reflections and maximizing energy transfer.

Simulation-based validation (S-parameters, field distributions) is a powerful design tool for RF systems.

