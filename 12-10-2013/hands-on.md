Introduction
============

1. [Source the environment](#source-the-environment)
2. [Created a catkin workspace](#create-a-catkin-workspace)
3. [Build](#build)
4. [Source the workspace](#source-the-workspace)

[Click to open then copy todo-list](https://trello.com/b/2k5dmOvG/ros)

----


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
