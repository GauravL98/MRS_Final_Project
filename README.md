<div align="center">
<h1>MAE 598 Multi Robot Systems</h1>

<h2>Collective Intelligence for Swarm in Target Search Scenario</h2><br>
<h3>Instructor: Prof. Spring Berman<h3> <br>
</div>
Team Members:<br> 
1) Monark Bandishbhai Parekh&nbsp;&nbsp mparekh2@asu.edu&nbsp;&nbsp 1222179426<br>
2) Gaurav Lavadiya&nbsp;&nbsp;&nbsp;&nbsp&nbsp;&nbsp&nbsp;&nbsp&nbsp;&nbsp&nbsp;&nbsp&nbsp;&nbsp&nbsp;&nbsp&nbsp;&nbsp&nbsp;&nbsp&nbsp glavadiy@asu.edu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp 1222768924<br>

<div align="center">
<h3>Abstract</h3>
</div>
An Unmanned Aerial Vehicle (UAV) swarm has many applications like monitoring, surveillance, and search missions. For this project, we have focused on the use of UAV swarm in search missions. We have implemented different search patterns with a UAV swarm to search for a target in a pre-defined space. The application we are working on is to find a person using the UAV Swarm, who is lost in the given area. The search area will be fixed but the obstacles will be unknown to the drones. So, Drone will start looking for the person with a search pattern and once one drone finds the target, the other drones will go to the target and hover over the target. The dynamics of the UAVs are modeled with the steering force method and for guiding moment and collision avoidance potential field model is used. The bivariate function is used as a potential field to contain multiple drones within an elliptical area for formation flight and calculate velocity to further find the force acting on the drones using the controller. We have implemented distributed decision-making to provide autonomy to UAVs, combined with the development of a collective intelligence module for the coordination of the swarm, with a shared discrete map search strategy for the search mission of the missing target. Collision avoidance, stability, and convergence are swarm behaviors that we have analyzed in this project. We have conducted a theoretical analysis of swarm stability and convergence. We have simulated the project using pygame and for validation, we have submitted two videos. The first video shows that the drone swarm is stable, and drones do not collide with each other. While the second video shows that the drones will converge on the desired target. A final working video is also provided which depicts the entire simulation. The plot of mission completion time vs drones and is also provided, analyzed and explained. <br>
<br>

This repo consists of the following files: 
<br>
1) constants.py -- Contains all the parameters for the simulation<br>
2) grid.py -- Grid generation Logic<br>
3) main.py -- Main File<br>
4) obstacle.py -- Obstacle generation Logic<br>
5) scan.py -- Search strategies Logic<br>
6) simulation.py -- Logic to generate Simulation using Pygame<br>
7) state_machine.py -- Implementation of the decision making (State Machine and Behaviors)<br>
8) utils.py -- Useful Functions<br>
9) vehicle.py -- Implementation of the vehicle (drone) logic<br>

<br> Videos:<br> 
Simulation of a Collective Intelligence for Swarm in Target Search Scenario -  https://youtu.be/2UDG6_ZfLZc<br>
Validation for the Stability and Collision Avoidance of the Swarm - https://youtu.be/JjUHQjxWVYQ<br>
Validation for the Convergence of the Swarm - https://youtu.be/-V3oR-y56ks <br>
