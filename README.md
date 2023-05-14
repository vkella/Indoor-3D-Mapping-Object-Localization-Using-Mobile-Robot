# Indoor-3D-Mapping-Object-Localization-Using-Mobile-Robot
We propose an incremental method for 3D mapping and object localization utilizing a stereo camera.

## To Build
```shell
1. git clone https://github.com/vkella/Indoor-3D-Mapping-Object-Localization-Using-Mobile-Robot.git
2. git clone https://github.com/vkella/realsense.git
3. git clone https://github.com/vkella/darknet_ros.git
4. sudo apt install ros-melodic-navigation
5. sudo apt install ros-melodic-jsk*
6. sudo apt install ros-melodic-jsk*
7. sudo apt install ros-melodic-rtabmap-ros
8. catkin build robot_3dslam

```
## To Run 
Launch Three Terminals 

Terminal 1
```shell
roslaunch robot_3dslam robot_world.launch

```
Terminal 2
```shell
roslaunch robot_3dslam robot_rtabmap.launch

```
Terminal 3
```shell
roslaunch explore_lite explore.launch

```

