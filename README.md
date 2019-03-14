# Turtlebot_HokuyoKinect_Gazebo
Add Hokuyo into the turtlebot in the gazebo(Indigo)

1. mkdir ros_sim/src
2. git clone
3. gedit ~/.bashrc 
   add:source /home/turtlebot/ros_sim/devel/setup.bash
       export TURTLEBOT_BASE=kobuki  
       export TURTLEBOT_STACKS=hexagons
       export TURTLEBOT_3D_SENSOR=KinectHokuyo
       
       #export TURTLEBOT_3D_SENSOR=kinect
4. source ~/.bashrc
5. cd /ros_sim  catkin_make
6. source devel/setup.bash
7. roslaunch robot_hokuyo_kinect my_world_hk.launch 
