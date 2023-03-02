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

```shell
roscore
```

## Run the tracking algorithm

```shell
rosrun object_tracking build/devel/lib/object_tracking/object_tracking_node
```
