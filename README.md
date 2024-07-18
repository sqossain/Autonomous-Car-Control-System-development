# Autonomous-Car-Control-System-development
Autonomous Car Control System development through Image processing with C++
This project was completed as a requirement for the Industrial Automation course (MECH 472/6631) in the Master's of Engineering program in Mechanical Engineering at Concordia University in Montreal, Quebec, Canada.

A robotics simulation environment was developed using C++ to create two distinct behavioral modes for a robot: evading and attacking a manual opponent. The implementation required comprehensive image processing, computer vision techniques, and precise robot control to achieve these behaviors.

For the evading behavior, the robot was configured to navigate around obstacles and the opponent robot. The process began with initializing the vision and simulation libraries, followed by acquiring and processing images to detect obstacles and opponents. The centroid method was used to identify the positions of detected objects and calculate angles. A control loop was implemented to navigate and avoid obstacles using these calculations, adjusting the robot's speed and direction based on proximity to obstacles and boundaries.

In the attacking behavior, the robot was programmed to track and attack the opponent robot. Similar to the evading mode, the vision and simulation libraries were initialized, and images were processed to locate the opponent. Centroids were calculated to determine positions, and a control loop was employed to track and approach the opponent. The robot's speeds and directions were adjusted to align with the opponent, and the laser was fired when in range and properly aligned, simulating a successful attack.

The primary tasks involve:

Evading Behavior:

1. Configure the robot to evade obstacles and the opponent robot.
2. Implement image processing to detect obstacles and the opponent robot.
3. Use the centroid method to identify positions and calculate angles.
4. Implement a control mechanism to evade obstacles and boundaries.
   
Attacking Behavior:

1. Configure the robot to track and attack the opponent robot.
2. Use image processing to identify and locate the opponent.
3. Implement an attacking strategy based on distance and angle calculations.
4. Control the robot's movement and firing mechanism to attack the opponent.

Work done:

Evading Mode:

1. Initialize the vision and simulation libraries.
2. Acquire and process images to detect obstacles and opponents.
3. Calculate centroids and determine positions.
4. Implement a control loop to navigate and avoid obstacles using angle and distance calculations.
5. Adjust robot speeds and directions based on proximity to obstacles and boundaries.

Attacking Mode:

1. Initialize vision and simulation libraries.
2. Process images to locate the opponent.
3. Calculate centroids and positions.
4. Implement a control loop to track and approach the opponent.
5. Adjust speeds and directions to align with the opponent.
6. Fire the laser when in range and aligned.


As a result, in the evading mode, the robot successfully detected and navigated around obstacles and the opponent, dynamically adjusting its path to avoid collisions while maintaining safe distances from boundaries. In the attacking mode, the robot effectively tracked and approached the opponent, aligned itself for an optimal attack, and fired the laser accurately when in range, demonstrating successful simulated attacks on the opponent.
