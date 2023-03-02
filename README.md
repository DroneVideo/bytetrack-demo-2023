# bytetrack-demo-2023

NanoDet + BYTETrack for uauv comp.

Link to [Setup](https://github.com/DroneVideo/docs/blob/gh-pages/setup.md)

## Build

```shell
cd ~/catkin_ws/src/object_tracking
mkdir build
cd build
cmake ..
make
```
## Initialize ROS

To run any ROS topic:

```shell
roscore
```

## Run the tracking algorithm

Open a new terminal

```shell
rosrun object_tracking build/devel/lib/object_tracking/object_tracking_node
```
