# AIGridSim
Probabilistic Cost Analysis of Installing PV and Storage using Simulation

AIGridSim takes four types of input files, those should be placed under AIGridSim/data:

-1 A file named Param.csv specifying the different parameters for the current analysis

-2 A file named Electric_Rates.csv specifying the different costs for electricity supply

-3 Histrorical Demand and Irradation files named Irradiadtion_i.csv and Demand_i.csv where i = 0..nb_years_analysis, each file contains an hourly input of total load and irradiation for a whole year, see the given files for an example.
