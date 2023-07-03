# Distributed-Coordination-for-Inverter-Air-Conditioner
These codes correspond to the simulation section of the paper "A Distributed Coordinated Framework with Fair Comfort Level Sharing for Inverter Air Conditioner in Auxiliary Services ". The software used is matlab 2021a, there are several files. 

1.TimeDelay.mlx is the simulation file of IACs tracking the reference aggregated power(step or random fluctuation) with different time-delays.

2.ToleranceCalculator.mlx can calculate the time-delay tolerance (Please determine the communication topology, IACs parameters and controller parameters first).

3.PrimaryControl.mlx is the simulation file of primary frequency support with IACs participation.

4.PeriodicIssue.mlx is a comparison simulation.

5.ComprehensiveSimulation.mlx is the simulation case when multiple non-ideal factors exist in whole control system.

These files contain notes about how to use them. If there are any problem, please contact with zhenweiyu@whu.edu.cn 
