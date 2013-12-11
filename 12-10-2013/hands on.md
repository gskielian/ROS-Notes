Introduction
============

1. Source the environment
2. Created a catkin workspace
3. Build
4. Source the workspace

![Click here to download the todo list]

Source the environment
----------------------

`source /opt/ros/hydro/setup.bash`

Create a catkin workspace 
-------------------------

```bash
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
catkin_init_workspace
```


build
------

```bash
cd ~/catkin_ws/
catkin_make
```

Source the workspace
--------------------


```bash
source devel/setup.bash
```
