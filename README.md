# Overview
These are the results from a live demonstraion in ME495 Embedded Systems in Robotics.  Project was created on 10/8/2020.  Handle with care.

# Usage Instructions
1. To start running the ciruclar trajectory and picture it in =rviz= run
   `roslaunch demo1 demo.launch`
2. `rqt_plot /point` to see the coordinates in `rqt_plot`
3. [plotjuggler](https://wiki.ros.org/plotjuggler) can be used to make an `xy` plot.

## Plot Juggler
1. Install `plotjuggler` with `sudo apt install ros-noetic-plotjuggler`
2. To make an `xy` plot in plot juggler, subscribe to the `point` topic
   then right-click drag the `x` and `y` topics into the plotting area