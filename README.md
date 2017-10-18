Repository includes Evarobot Simulator that simulator of robot which produced by İnovasyon Mühendislik with different worlds.
Launch files and robot model were built for Ros Kinetic and Gazebo 7.Some models in the worlds may not be seen on different versions of Gazebo.

To download and run launch files:
#### 1. You need interactive marker twist server. $ sudo apt-get install ros-kinetic-interactive-marker-twist-server 
#### 2. $ cd catkin_ws/src/
#### 3. $ git clone https://github.com/inomuh/uplat
#### 4. $ cd ~/catkin_ws
#### 5. $ catkin_make
#### 6. $ . ~/catkin_ws/devel/setup.bash
To run launch worlds your GAZEBO_MODEL_PATH should be directed to your uplat directory.
#### 7. $ gedit ~/.bashrc
In your bashrc file copy and paste to below commands
#### $ source /usr/share/[your gazebo version]/setup.sh
#### $ export GAZEBO_MODEL_PATH=/home/[your username]/catkin_ws/src/uplat/
To run launch files write the command below on terminal
#### $ roslaunch [folder name in uplat]_gazebo evarobot.launch -> example roslaunch evarobotlabirent_gazebo evarobot.launch
