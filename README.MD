# Obstacle Avoidance Method; Discontinue

This project performs a fully autonomous navigation, with online obstacle avoidance algorithms, using image output from **Guidance SDK** to detect obstacles and implement avoidance strategy via control input to **Onboard SDK**. This project is build on **ROS**. It contains the methods to stop the navigation when meet the obstacle.

## How To Run

1. Install ROS .
2. mkdir the directory in catkin workspace.
3. Build the project: `catkin_make`
4. Run the command: `sudo ./devel/lib/dji_sdk/dji_sdk_node`
5. Press Enter to end autonomous navigation

