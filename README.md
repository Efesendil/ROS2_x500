# ROS2_x500
Simulation environment for our master's project Low Cost IMU - Observer Implementation.

This project could be used for any other future work.

-----
1. Install ROS2-foxy
2. Clone the repo
3. Add this to .bashrc:

  source /opt/ros/foxy/setup.bash
  
  source /usr/share/gazebo/setup.sh
  
  export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:/home/<pc_name>/sim_ws/src/simulation/models/
  
4. colcon build
5. cd sim/ws
6. colcon build
7. install/setup.bash
8. source ~/.bashrc
9. gazebo
10. Find model x500 in gazebo
