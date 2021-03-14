# Obstacle_Avoidance_using_ROS
1. Clone this repo
2. catkin_make
3. sorce devel/setup.bash
4. In another terminal, do roscore
5. rosrun gazebo_ros gazebo
6. roslaunch m2wr_description spawn.launch
8. rosrun motion_plan obstacle_avoidance.py

To visualise obstacles in rviz:
1. roscore
2. rosrun gazebo_ros gazebo
3. roslaunch m2wr_description spawn.launch
4. roslaunch m2wr_description rviz.launch
5. Add Robotstate and Laserscan in rviz
6. Change topic to /odom

For gmapping
1. Do above steps and add map in rviz
2. Move robot in gazebo using teleop_twist and see map in rviz
Reference link:https://www.theconstructsim.com/exploring-ros-2-wheeled-robot-part-5/


