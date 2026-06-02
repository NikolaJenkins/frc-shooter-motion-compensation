For the FRC 2026 challenge Rebuilt, my team created a robot with the goal of scoring game pieces on the move. 

In order to do this, I used regression models to calculate the turret hood's angle and the flywheel velocity based on the robot's distance from the target. I combined these values with the turret's angle to create a launch vector as if the robot was stationary. I then compensated for the robot's motion by subtracting its velocity vector from the stationary launch vector. This adjusted vector was the one the game pieces were actually launched at.



https://github.com/user-attachments/assets/4a04168d-dd82-4112-9cca-6249a7af90a2
