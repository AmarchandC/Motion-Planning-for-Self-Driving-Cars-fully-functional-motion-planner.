# Motion-Planning-for-Self-Driving-Cars-Smooth Local Planner.
Project Description:

Implemented a functional motion planning stack capable of avoiding static and dynamic obstacles while tracking the center line of a lane and handling stop signs.
Implemented behavioral planning logic, static collision checking, path selection, and velocity profile generation to achieve the project goals.
Utilized the CARLA simulator and the provided assignment code to develop and test the motion planning system.
Technical Implementation:

Edited and implemented functionality in key class files, including "behavioural_planner.py," "collision_checker.py," "local_planner.py," "path_optimizer.py," and "velocity_planner.py."
Implemented a state machine-based behavioral planning logic, enabling smooth transitions between lane following, deceleration to stop signs, and back to lane following.
Developed path generation algorithms, including computing goal state sets, spiral path generation, and path optimization.
Implemented circle-based collision checking to ensure the planned paths are free from static obstacles.
Employed path selection techniques to evaluate objective functions and select the best path, considering both obstacle avoidance and centerline tracking.
Generated velocity profiles considering stop signs, lead dynamic obstacles, and nominal lane maintenance using physics-based functions.
Simulation and Evaluation:

Utilized the CARLA simulator to test and validate the implemented motion planning stack.
Ran the simulator with the completed implementation to assess the performance and functionality of the motion planning system.
