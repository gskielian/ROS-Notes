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
