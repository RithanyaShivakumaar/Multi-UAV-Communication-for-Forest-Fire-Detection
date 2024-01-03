# Multi-UAV-Communication-for-Forest-Fire-Detection
A NetSim-Matlab-based project that simulates the performance analysis of a Multi-UAV - Base Station network for communications in the application of forest fire monitoring and detection.

# Procedure and Explanation

1. Install required softwares : Matlab and Netsim

2. Interface Matlab and Netsim
	Ref. document : https://support.tetcos.com/support/solutions/articles/14000138708-how-to-interface-netsim-and-matlab-
3. Open Matlab-Simulink Files
	Path : SourceCode\LTE-UAV-Simulation_v12.2-main\MATLAB-Files
4. Open Netsim Files 
	Existing support files(Single UAV Commn.) : SourceCode\LTE-UAV-Simulation_v12.2-main\4G_UAV_Simulation_Workspace\Experiment_LTE\configuration.netsim
	Improved novelty(Multi-UAV Commn.)  : SourceCode\Experiment_LTE_interuav\configuration.netsim

UAV has properties such as ID, location, communication capabilities, and path-following algorithms.
simulates the movement of a single UAV based on predefined paths and environmental conditions
MATLAB plotting functions visualizes the UAV's movement along the predefined path in 2D, considering environmental factors.
MATLAB calculates the flight path. The X, Y and Z coordinates obtained from SIMULINK are read from MATLAB workspace and given as input to NetSim's Mobility model. 
In NetSim UE movement is modelled as per MATLAB UAV co-ordinates
