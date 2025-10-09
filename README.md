# RDD2 Mocap
-------------
This is a test workspace for the RDD2 for use with the PURT mocap sytem.

## Initial Setup
```bash
mkdir -p ~/ws_rdd2_mocap/src
cd ~/ws_rdd2_mocap/src
git clone git@github.com:jgoppert/rdd2_mocap
cd ~/ws_rdd2_mocap/
vcs import < src/rdd2_mocap/repos.yaml
colcon build --symlink-install
. ./install/setup.bash
ros2 launch rdd2_mocap test.xml
```

## Update
```bash
cd ~/ws_rdd2_mocap/src
vcs pull
colcon build --symlink-install
. ./install/setup.bash
```

