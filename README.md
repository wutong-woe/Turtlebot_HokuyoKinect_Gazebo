# Turtlebot_HokuyoKinect_Gazebo
Add Hokuyo into the turtlebot in the gazebo(Indigo)

1. mkdir ros_sim/src
2. git clone
3. gedit ~/.bashrc 
4. add:source /home/turtlebot/ros_sim/devel/setup.bash
       export TURTLEBOT_BASE=kobuki  
       export TURTLEBOT_STACKS=hexagons
       export TURTLEBOT_3D_SENSOR=KinectHokuyo
       注释掉export TURTLEBOT_3D_SENSOR=kinect
5. source ~/.bashrc
6. cd /ros_sim  catkin_make
7. source devel/setup.bash
8. roslaunch robot_hokuyo_kinect my_world_hk.launch 
