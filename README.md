# Hector_slam.
Hector slam stack for mapping ..

This packge entails a ros package for mapping "Hector slam".

To install hector mapping stack,type the following command below:
```
sudo apt-get install ros-<ros_distro>-hector-slam
```
clone the package into your src of your workspace:
```
mkdir -p ~/catkin_ws/src
cd catkin_ws
cd src
```
Launching the hactor slam Node:
```
roslaunch hector_slam_launch tutorial.launch 
```
Open rviz on a new terminal:
```
rosrun rviz rviz
```
Add the topics below to visualize the map generated by the Node,while the lidar publishes a laser_scan.
1. Map.
2. laser_scan.
3. TF.

Set the rviz fixed frame to:
- Map.

You should see the map publsihed to rviz now.Keep Mapping...........
