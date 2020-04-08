# Home Service Robot
I combined everything I’ve learned in this program to simulate a home service robot that can map, localize, and navigate to transport objects, moving from one room to another autonomously. 

## Official ROS packages
Import these packages now and install them in the src directory of your catkin workspace. Be sure to clone the full GitHub directory and not just the package itself.

- [gmapping](http://wiki.ros.org/gmapping): With the gmapping_demo.launch file, you can easily perform SLAM and build a map of the environment with a robot equipped with laser range finder sensors or RGB-D cameras.
- [turtlebot_teleop](http://wiki.ros.org/turtlebot_teleop): With the keyboard_teleop.launch file, you can manually control a robot using keyboard commands.
- [turtlebot_rviz_launchers](http://wiki.ros.org/turtlebot_rviz_launchers): With the view_navigation.launch file, you can load a preconfigured rviz workspace.
- [turtlebot_gazebo](http://wiki.ros.org/turtlebot_gazebo): With the turtlebot_world.launch you can deploy a turtlebot in a gazebo environment by linking the world file to it.
## My Packages and Directories
I installed these packages and created the directories as I went through the project.

- map: Inside this directory, I stored my gazebo world file and the map generated from SLAM.
- scripts: Inside this directory, I stored my shell scripts.
- rvizConfig: Inside this directory, I stored my customized rviz configuration files.
- pick_objects: I wrote a node that commands my robot to drive to the pickup and drop off zones.
- add_markers: I wrote a node that models the object with a marker in rviz.
