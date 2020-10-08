# coppeliasim_ros_services

this package is an update of the [vrep_plugin] package which creates ros service servers to enable a remote-control of the [coppeliasim][] simulator. the new package coppeliasim_ros_services is compatible with Coppeliasim v4.0.

### Dependencies
- [coppeliasim_msgs_srvs][]: it contains definitions of required messages and services which enables ros to communicate with coppeliasim.

### Building 

The following instructions assume that a catkin workspace has been created at `$HOME/catkin_ws` and Coppeliasim directory is placed at the Home directory `$HOME/CoppeliaSim`. you always can update the paths based on your machine setup.

```bash
# change to the src directory in your Catkin workspace
cd $HOME/catkin_ws/src

# Clone Coppeliasim_ros_control pkg 
git clone https://github.com/mahmoud-a-ali/coppeliasim_ros_services

# change to the main Catkin workspace
cd ..

# build the workspace (using catkin_tools)
 catkin build
 
 # activate your workspace
 source $HOME/catkin_ws/devel/setup.bash
```

### Running




### Example
Refer to [ur5_coppeliasim_roscontrol][] package on how you can use the coppeliasim_ros_services plugin to control the simulation inside coppeliasim simulator using ros.

[coppeliasim_msgs_srvs]: https://github.com/mahmoud-a-ali/Coppeliasim_msgs_srvs
[vrep_plugin]: https://github.com/jocacace/vrep_plugin
[coppeliasim]: https://www.coppeliarobotics.com/
[ur5_coppeliasim_roscontrol]: https://github.com/tud-cor/ur5_coppeliasim_roscontrol
