# RBGD-Mapping-
Navigation with RTAB-Map and Hector-SLAM
## The Simultaneous Localization and Mapping (SLAM)
 * problem asks if it is possible for a mobile robot to be placed at an unknown location in an unknown environment and for the robot to incrementally build a consistent map of this environment while simultaneously
determining its location within this map. A solution to the SLAM problem has been seen as a holy grail for the mobile robotics community as it would provide the means to make a robot truly autonomous. 

* SLAM is an essential task for the autonomy of a robot. Nowadays, the problem
of SLAM is considered solved when range sensors such as lasers or sonar are used to built 2D maps of small static environments. However for large-scale long-term SLAM, robot has to deal with unknown initial positioning caused by either the kidnapped robot problem or multi-session mapping.

* The objective of this thesis is to implement one or more functionalities based on camera-based sensors in a mobile autonomous robot. A mobile robot prototype has been configured to run ROS (Robot Operating System), a middleware framework that is suited to the development of robotic systems. The system uses RTAB-Map (Real-Time Appearance Based Mapping) to survey
the surroundings and a built navigation stack in ROS to navigate autonomously against easy targets in the map. The method uses a Kinect for Xbox 360 for create 3D map,a 2D laser scanner as the main sensor and wheel encoder for odometry. Test results, obtained from both live and simulated trials, indicate that the robot is able to form 3D and 2D map of the surroundings. 
* The method has weaknesses that are related to the ability to find visual features. Further testing has demonstrated that the robot can navigate autonomously, another 2D SLAM method call Hector SLAM was implemented to combined with RTAB-Map also gave good result, but there is still room for improvement. Better results can be achieved with a new movable platform and further tuning of the system. In conclusion, ROS works well as a development tools for robots, and the current system is suitable for further development. Hector SLAM and RTAB-Map can combined together to get a better result in mapping. RTAB-Maps suitability for use on an industrial installation is still uncertain and requires further testing.

