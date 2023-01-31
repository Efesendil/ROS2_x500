# ROS2_x500
Simulation environment for our master's project Low Cost IMU - Observer Implementation.

This project could be used for any other future work.

-----
1. Install ROS2-foxy
2. Create workspace "sim_ws/src", create folder "simulation" in src, go to "simulation"
2. Clone the repo
3. Add this to .bashrc:

  source /opt/ros/foxy/setup.bash
  
  source /usr/share/gazebo/setup.sh
  
  export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:/home/<pc_name>/sim_ws/src/simulation/models/
 
4. cd sim/ws
5. colcon build
6. install/setup.bash
7. source ~/.bashrc
8. gazebo
9. Find model x500 in gazebo
