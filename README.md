# warehouse_tasker_interfaces
Interfaces with the warehouse_tasker ROS package

see the [warehouse_tasker](https://github.com/imJohly/warehouse_tasker) package for more info.

# How to install

Clone the repo into your ROS2 workspace,

```bash
cd ~/<your ros2_ws here>/src
git clone git@github.com:imJohly/warehouse_tasker_interfaces.git
```

Build the package using colcon and source if from the install directory,

```bash
cd ..
colcon build --symlink-install --packages-select warehouse_tasker_interfaces
source install/local_setup.bash
```
