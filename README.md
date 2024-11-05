Robotics Simulation with ROS2 and TurtleBot


This README outlines the key tasks and learnings from the workshop on using ROS2 for robotics simulation and control, specifically with the TurtleBot in a Gazebo environment.

Workshop Goals


Understand and use basic Linux terminal commands.
Get familiar with ROS2 basics, including installation, setup, and commands.
Create a ROS2 package and integrate Python scripts.
Launch and control a TurtleBot in simulation using VS Code, Gazebo, and RViz.
Simulate bot movement and map the environment for autonomous navigation.
Workshop Steps
Basic Linux Terminal Commands

Objective: Familiarize with fundamental Linux commands.
Commands Covered:
Navigation: ls, cd, pwd.
File operations: mkdir, touch, rm, cp, mv.
Permissions: chmod, chown.
Outcome: Learned efficient navigation and file handling in the Linux terminal, essential for ROS2 package management.
Introduction to ROS2

Objective: Understand the basics of ROS2 (Robot Operating System 2).
Topics Covered:
ROS2 architecture and components.
Basic ROS2 commands: ros2 topic, ros2 node, ros2 service.
Outcome: Gained foundational knowledge of ROS2, a middleware for robotic applications.
Creating the First ROS2 Package

Objective: Set up a new ROS2 package and integrate Python scripts.
Steps:
Created a ROS2 package using colcon build tool.
Added Python scripts within the package for robot control and simulation tasks.
Outcome: Successfully built and executed a custom ROS2 package.
Drawing a Circle with TurtleBot in VS Code

Objective: Use VS Code to launch TurtleBot and draw a circle in simulation.
Steps:
Configured VS Code for ROS2 development.
Launched the TurtleBot simulation and executed commands to make the bot trace a circular path.
Outcome: Acquired hands-on experience in bot control and ROS2 integration with VS Code.
![image](https://github.com/user-attachments/assets/36db6d2c-6913-4e53-9bf5-ca8c2cf0faff)
Launching Gazebo with TurtleBot Waffle and Obstacles
Objective: Simulate a TurtleBot Waffle in Gazebo with obstacles.
Steps:
Selected the TurtleBot Waffle model.
Launched a Gazebo environment with pre-defined obstacles for navigation challenges.
Outcome: Gained familiarity with Gazebo simulation environment and TurtleBot models.
![image](https://github.com/user-attachments/assets/8e71aae8-e954-449b-a009-bba0644856e9)
Bot Control with teleop_key
Objective: Manually control the TurtleBot using keyboard commands.
Steps:
Used teleop_key command to navigate the bot within the Gazebo environment.
Simulated obstacle avoidance and navigation in real-time.
Outcome: Learned the basics of teleoperation and manual control for robots.
![image](https://github.com/user-attachments/assets/9f473706-fdb3-46fd-be1e-2e9b425a801e)
Mapping the Area with RViz for Automatic Simulation
Objective: Map the Gazebo environment using RViz for autonomous bot navigation.
Steps:
Launched RViz alongside Gazebo to visualize and map the simulated area.
Used the map for autonomous pathfinding and area coverage by the TurtleBot.
Outcome: Successfully mapped the environment and set up the TurtleBot for automatic navigation in simulation.

![image](https://github.com/user-attachments/assets/17e3eece-a814-4df8-89ad-da6ab9f17eb8)
Summary of Learnings
This workshop provided practical experience in robotics simulation using ROS2, Gazebo, and RViz, enabling better understanding of robot control, mapping, and simulation environments. By the end, participants were able to:

Navigate and use Linux commands for ROS2 tasks.
Create and manage ROS2 packages with Python integration.
Simulate, control, and map environments with TurtleBot in Gazebo and RViz.

