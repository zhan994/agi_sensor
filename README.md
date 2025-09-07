# agi_sensor
**A repo. which maintains sensor pkgs for agi-robotics.**

- fdilink_ahrs: for FDISYSTEMS Deta10 9-axis IMU, validated VINS-Mono system using a low-price global-shutter gray camera.
- icm20948: for DIY 9-axis IMU using ICM-20948.
- lakibeam1: for RichBeam LakiBeam1L 2D LiDAR.


## Run

```bash
mkdir -p ws_sensor/src
cd ws_sensor/src
git clone git@github.com:zhan994/agi_sensor.git
cd ..
catkin_make
```
