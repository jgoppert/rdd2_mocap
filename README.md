# RDD2 Test
-------------

```bash
mkdir -p ~/ws_rdd2_test/src
cd ~/ws_rdd2_test/src
git clone git@github.com:jgoppert/rdd2_test
cd ~/ws_rdd2_test/
vcs init src/rdd2_test/rdd2_test.yaml
vcs pull
colcon build --symlink-install
. ./install/setup.bash
ros2 launch rdd2_test test.xml
```
